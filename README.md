Toolchain
=========
Set of features and updatesite forthe CloudScale Toolchain - Analyser, Extractor, Static Spotter and Dynamic Spotter.
Each feature contains all 3rd party tool dependencies.

Build and package updatesite
-----------------------------------------

1. Clone the repository.
	* `$ cd Cloudscale`
	* `$ git clone https://github.com/CloudScale-Project/Toolchain.git`
2. Build Cloudscale Environemnt.
	* `$ mvn clean package`
3. Publish update site
	* Updatesite repository : features/eu.cloudscaleproject.updatesite.toolchain/target/repository
	* In eclipse use local update site (or host entire repository online)
