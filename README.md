maven customer plugin demo

# command

mvn archetype:generate with number 1459
mvn install
mvn org.sonatype.mavenbook.plugins:first-maven-plugin:1.0-SNAPSHOT:echo
mvn org.sonatype.mavenbook.plugins:first-maven-plugin:1.0-SNAPSHOT:echo -Decho.message="The Eagle has Landed"


add this to your ~/.m2/setting.xml:

<pluginGroups>
        <pluginGroup>org.sonatype.mavenbook.plugins</pluginGroup>
</pluginGroups>

then:

mvn first:echo

mvn myPlugin:zip-fork
mvn first:zip-fork

mvn firstant:echo
mvn firstant:echo -Dmessage="my world"

/usr/libexec/java_home
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_231.jdk/Contents/Home
mvn firstruby:echo -Dmessage="my hello"
mvn firstruby:test -Dprop="my string"

# This ruby plugin can be executed under maven 2.2.1, but not under maven 3.




