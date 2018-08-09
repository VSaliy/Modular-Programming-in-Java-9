javac --module-source-path src -d out src/packt.addressbook/packt/addressbook/Main.java src/packt.addressbook/module-info.java
java --module-path out --module packt.addressbook/packt.addressbook.Main

javac -d out --module-source-path src --module packt.addressbook
java --module-path out --module packt.addressbook/packt.addressbook.Main

javac -d out --module-source-path src --module packt.addressbook,packt.sortutil
java --module-path out -m packt.addressbook/packt.addressbook.Main