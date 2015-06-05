This code repository houses several programs that implement algorithms based on the Proximal Distance MM principle.

CONVEXCLUSTER is an implementation of convex clustering, a technique that is appropriate for inferring clusters dynamically, as in the case of hierarchical clustering. In contrast to hierarchical clustering, convex clustering is more accurate, robust to outliers, and versatile. In terms of versatility, convex clustering allows users to specify weights informed by expert domain knowledge and a desired level of granularity. CONVEXCLUSTER includes code written in OpenCL so that users with nVidia or ATI GPUs can apply convex clustering efficiently on high dimensional data.