## Pan3D Community

Pan3D is a 3D data and interactive visualization system to enable the creation of cohesive, efficient, and highly interactive workflows for n-dimensional scientific data. Pan3D aims to address major gaps in 3D data and modeling workflows by building some of the key data and visualization components and technologies that, when put together in a larger system, will provide an integrated, interactive, reproducible, and shareable 3D computing environment for domain scientists.

Pan3D will build and extend three core components for the 3D data and modeling workflow.

1. **3D Data interoperability**. This key innovation will give visualization systems direct access to raw data arrays for geometry attributes, partial or full data access, and multi-resolution views. In return, the modeling code will have direct access to data processed by visualization algorithms such as slicing, filtering, or contouring. Pan3D will work with data produced by numerical simulations in Network Common Data Form (NetCDF) and the Hierarchical Data Format (HDF) and data consumed and produced by AI/ML systems in NumPy structures. Pan3D will build N-D arrays interoperability with Kitware’s open source VisualizationToolkit (VTK/ParaView) data structures, a widely used library within DOE and industry.
2. **Scalable 3D visualization in interactive compute environments**. 3D visualization in computing environments enables users to more productively carry out their modeling workflows. Users won’t have to leave their current workflow in order to visualize inputs, intermediate results, and outcomes. Pan3D will be scalable and support large data rendering using multi-dimensional data indexing to request varying resolutions of the data dynamically. On HPC platforms, it will support a parallel server-side rendering to scale visualization. 
3. **Scientific Data access in workflows**. Through integration with existing open source data services such as Pangeo and STAC server, Pan3D will provide access to data in cloud-hosted interactive data modeling and visualization workflows. These data services will serve 2D and n-dimensional 3D data using open data standards and specifications such as FAIR data standards and STAC for raster, vector, and gridded data. For HPC and cloud hosted workflows, Pan3D will let users browse through and visualize the data in a new dataset builder feature. 

Pan3D will eliminate the learning curve requirements for visualization and provide scientists with a "one line of code" solution that minimizes data duplication and provides subsampled data extraction for visualizing large data sets.
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
