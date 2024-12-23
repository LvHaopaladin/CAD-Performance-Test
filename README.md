# CAD-Performance-Test

This tool is designed for evaluating the performance of 3D CAD software. It helps CAD software developers identify the performance gap between their products and industry-leading solutions. Additionally, it assists software users in selecting the most suitable CAD software for their needs. 
The tool also integrates functionality evaluation, which will be introduced in future updates.

## Download Files

To facilitate the direct reproduction of the Case Study, we have placed the testing tools, test cases, and several CAD software packages in a virtual machine. Due to file size limitations, the files have been split into multiple parts and stored in a cloud drive. The download instructions can be found in the `How to download.txt` file. We are continuously looking for more convenient download methods, and any updates will be posted in this file.

## Running the Virtual Machine

After extracting all the compressed files into the same folder, use VMware to run the `Windows 7 x64.vmdk` file. VMware version 17.6.0 has been tested and works successfully.

## Getting Test Data

1. Run the test tool '三维CAD性能分析与综合评价工具软件.exe'
2. Select the test cases by ticking the corresponding checkboxes in the case library.
3. Choose the 3DCAD system to be tested from the drop-down list and start the system.
4. Click the Run Test button ('执行测试'） to begin the automatic testing process, utilizing the selected test case(s).

The 3DCAD system will then automatically perform the modeling tasks of the selected test cases in sequence, according to their respective scripts. The corresponding performance data will be automatically saved in the appropriate files.
