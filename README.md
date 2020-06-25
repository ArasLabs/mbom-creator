# MBOM Creator

The MBOM Creator is a quick tool for making an MBOM, where you can use part by part additions as well as drag and drop from your EBOM to build out an MBOM.


## Project Details

Release | Notes
--------|--------
[v1.0](https://github.com/ArasLabs/project-plan-excel-export/releases/tag/v1.0) | First release. Built and tested on Aras Innovator 12 SP1.

#### Supported Aras Versions

Project | Aras
--------|------
[v1.0](https://github.com/ArasLabs/project-plan-excel-export/releases/tag/v1.0) | 12.0 SP1


## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed, of at least version 12 service pack 1.

### Install Steps

1. Backup your code tree and store the archive in a safe place
2. Open up the Aras Package Import Tool
3. Enter your login credentials and click login.
4. Enter the package name ("mbom-creator") in the TargetRelease field
5. Enter the path to your local ..\mbom-creator\Import\imports.mf file in the Manifest File field
6. Select MBOM_Creator in the Available for Import field.
7. Select Type = Merge and Mode = Thorough Mode.
8. Click Import in the top left corner.
9. Close the Aras Package Import tool.

## Usage

1. Login to Aras
2. Navigate to **Design > Parts** in the table of contents (TOC) and click Search
3. Right click on a Project item in the main grid and select **Create New MBOM**
4. From here, you can do several things:
	* Left click on the left to drag part of the EBOM over to the part you want it listed under, then release.
	* Right click on a part in your MBOM and click "Add Part", then select the part you want to add from the search grid.
	* Right click on a part in your MBOM and click "Add Phantom", then provide the information for your phantom.
	* Right click on a part in your MBOM and click "Remove Part"
5. When you're ready, click **Save** in the top right.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

For more information on contributing to this project, another Aras Labs project, or any Aras Community project, shoot us an email at araslabs@aras.com.


## Credits

Original Aras community project written by Skyler Crossman at Aras Corp.

Documented and published by Skyler Crossman for Aras Labs. @skycrossman


## License

This project is published to Github under the MIT license. See the [LICENSE file](./LICENSE.md) for license rights and limitations.