# Easy to Use Salesforce Migration ANT Tool
This repository contains a skeleton Salesforce project. The project contains the necessary build files to:
1. Create project manifest.
2. Retrieve components.
3. Deploy components.

## Getting Started
### Prerequisites
* Eclipse
* Force.com IDE 
* Ant and ant-contrib

### Build.Properties
#### Setup Ant Location
```
# Path where Apache ANT is located. Make sure lib/ant-salesforce.jar and lib/ant-contrib-1.0b3.jar exists
ant.home = /tools/apache-ant-1.10.1
```

#### Setup Login Credentials
```
sf.server.url = https://test.salesforce.com
#sf.serverurl = https://login.salesforce.com

sf.src.username = 
sf.src.password = 
sf.dest.username = 
sf.dest.password = 
```

#### Add/Remove Component Types
```
sf.metadataTypes.all = ...
sf.metadataTypes.unmanaged = ...
sf.metadataTypes.infolder.all = ...
sf.metadataComponents.exclude = ...
```

### Commands
* ant usage
* ant all
* ant build-manifest
* ant deploy




