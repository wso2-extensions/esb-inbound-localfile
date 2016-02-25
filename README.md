# LocalFile ESB Inbound

The WSO2 ESB local file custom inbound protocol is a multi-tenant capable alternative to file inbound protocol. Current file inbound support for ftp, sftp and local files, but local file inbound will only support for local files. The ESB file inbound protocol uses the VFS transport to process files in a specified source directory. The local file inbound uses java NIO API to process files in a specific directory. After processing the files, it moves them to a specified location or deletes them. 

##Build
mvn clean install

###How You Can Contribute

You can create a third party connector and publish in WSO2 Connector Store.

https://docs.wso2.com/display/ESBCONNECTORS/Creating+a+Third+Party+Connector+and+Publishing+in+WSO2+Connector+Store
