# SQL Server JDBC library with SSO for NetBeans

This plugin provides a SQL Server JDBC driver for Netbeans.

The [underlying driver](https://github.com/nbbrd/jtds-ntlmauth) uses the Windows authentication (NTLM) to connect to an instance of SQL Server.

## How to build

This project uses [Maven](http://maven.apache.org/) as a project builder.

To build this plugin, you need to:

1. Build the [driver](https://github.com/nbbrd/jtds-ntlmauth) first
2. Download the latest source code
3. Run `mvn clean build`
4. The generated library is available in the `target` directory and also in the local repository

## How to use

* Download the library [here](https://github.com/nbbrd/jtds-ntlmauth-netbeans/releases) or build it yourself
* The connection parameters are exactly the same as [jTDS](http://jtds.sourceforge.net/doc.html) except that you don't need to deal with the lib path
