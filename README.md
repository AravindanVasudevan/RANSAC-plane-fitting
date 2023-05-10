# RANSAC - plane fitting

This project is an implementation of the RANSAC algorithm, which is a robust estimation method designed to handle outliers and noise in the data to fit a plane onto a point cloud dataset using.

The project is implemented in Python using the Open3D library, which provides a set of tools for processing 3D data. The RANSAC algorithm is applied to point cloud data to identify the best-fit plane that represents the underlying structure of the data.

The image depicts the point cloud data:

<img width="181" alt="Screenshot 2023-05-10 003503" src="https://github.com/AravindanVasudevan/RANSAC-plane-fitting/assets/57245944/cd3d6878-87dc-4c65-8fe5-61f79d8dcdad">

The algorithm starts by randomly selecting a subset of points from the input point cloud and fitting a plane to those points. The algorithm then iteratively selects additional points that are consistent with the plane model and refits the plane. This process continues until the algorithm converges to a stable plane model that best fits the input data.

The results of the algorithm are visualized using the Open3D library. The input point cloud and the fitted plane are displayed in a 3D visualization.

The image depicts the point cloud data after the best plane is found:

<img width="234" alt="Screenshot 2023-05-10 003513" src="https://github.com/AravindanVasudevan/RANSAC-plane-fitting/assets/57245944/fd16912b-3ed9-46d4-a5b4-28512d28ae13">
