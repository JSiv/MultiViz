# Multiviz: A Gephi Plugin for Scalable Visualization of Multi-Layer Networks

Real-world networks are extremely difficult to visualize due to their immense complexity. MultiViz is a plugin for Gephi, an open-source software tool for graph visualization and modification, which can be used to visualize complex networks in a multilayered fashion. A collection of settings are available through the plugin to transform an existing network into a multi-layered network. The plugin supports several layout algorithms and lets the user choose which property of the network to be used as the layer. The goal is to provide the user with complete control over how the network is visualized in a multi-layer fashion.

Preprint available at: https://arxiv.org/abs/2209.03149

## Get started

Once available in the Gephi platform, the multiviz plugin can be installed from the Gephi application itself by navigating to the `Tools` > `Plugins` option in the application.

### Steps to run the plugin locally

1. Download the project from GitHub
    
       https://github.com/JSiv/gephi-plugins

2. Start [Apache Netbeans IDE](https://netbeans.apache.org/) and go to `File` and then `Open Project`. 
3. Navigate to the project files, Netbeans will automatically recognize it as a Maven project.
4. Open the Terminal window in Netbeans by going to `Tools` > `Open in Terminal`
5. Run the following command to compile and build the plugin:

       mvn clean package

6. Run the following command to run Gephi with the multiviz plugin pre-installed

       mvn org.gephi:gephi-maven-plugin:run

7. After Gephi is opened, Generate/ Import a network graph
8. To open the plugin, Select `Multi Layer Visualization` in the `Layout` tab in Gephi.
9. Try different settings and values in the plugin to create a good visualization
10. Check out the finalized visualization on the preview page and export it as pdf, svg, or png.

### Demo 
Watch how to use the plugin [here](https://youtu.be/asGfis-cRwg)

### Requirements

Running the multiviz plugin requires [Apache Netbeans](https://netbeans.apache.org/), [JDK](https://www.oracle.com/java/technologies/downloads/) 11 or later and [Maven](http://maven.apache.org/).

# Cite MultiViz

If you find MultiViz useful in your research, please add the following citation.

```
@misc{https://doi.org/10.48550/arxiv.2209.03149,
  doi = {10.48550/ARXIV.2209.03149},
  url = {https://arxiv.org/abs/2209.03149},
  author = {S., Jayamohan Pillai C. and Chatterjee, Ayan and M., Geetha and Mukherjee, Amitava},
  keywords = {Social and Information Networks (cs.SI), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {MultiViz: A Gephi Plugin for Scalable Visualization of Multi-Layer Networks},
  publisher = {arXiv},
  year = {2022},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
