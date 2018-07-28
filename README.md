javac --module-source-path src -d out src/packt.addressbook/packt/addressbook/Main.java src/packt.addressbook/module-info.java
java --module-path out --module packt.addressbook/packt.addressbook.Main