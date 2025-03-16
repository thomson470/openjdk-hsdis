# OpenJDK hsdis (HotSpot disassembly plugin)


| Operating System | CPU              | Architecture | Download                                                                                                              |
| :----------------- | :----------------- | :------------- | :---------------------------------------------------------------------------------------------------------------------- |
| Linux            | AMD/Intel 64-bit | amd64        | [hsdis-amd64.so](https://raw.githubusercontent.com/thomson470/openjdk-hsdis/refs/heads/main/hsdis-amd64.so)           |
| Linux            | ARM 64-bit       | aarch64      | [hsdis-aarch64.so](https://raw.githubusercontent.com/thomson470/openjdk-hsdis/refs/heads/main/hsdis-aarch64.so)       |
| Linux            | ARM 32-bit       | arm          | [hsdis-arm.so](https://raw.githubusercontent.com/thomson470/openjdk-hsdis/refs/heads/main/hsdis-arm.so)               |
| Windows          | AMD/Intel 64-bit | amd64        | [hsdis-amd64.dll](https://raw.githubusercontent.com/thomson470/openjdk-hsdis/refs/heads/main/hsdis-amd64.dll)         |
| Windows          | AMD/Intel 32-bit | i386         | [hsdis-i386.dll](https://raw.githubusercontent.com/thomson470/openjdk-hsdis/refs/heads/main/hsdis-i386.dll)           |
| MacOS            | Intel 64-bit     | amd64        | [hsdis-amd64.dylib](https://raw.githubusercontent.com/thomson470/openjdk-hsdis/refs/heads/main/hsdis-amd64.dylib)     |
| MacOS            | ARM 64-bit       | aarch64      | [hsdis-aarch64.dylib](https://raw.githubusercontent.com/thomson470/openjdk-hsdis/refs/heads/main/hsdis-aarch64.dylib) |

The JDK will look for the hsdis binary in the following paths:

* &lt;JDK_HOME&gt;/lib/server/hsdis-&lt;arch&gt;.&lt;extension&gt;
* &lt;JDK_HOME&gt;/lib/hsdis-&lt;arch&gt;.&lt;extension&gt;
