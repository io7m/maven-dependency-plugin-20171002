Apache Maven 3.5.0 (NON-CANONICAL_2017-04-10T13:56:20+03:00_root; 2017-04-10T10:56:20Z)
Maven home: /opt/maven
Java version: 9, vendor: Oracle Corporation
Java home: /usr/lib/jvm/java-9-openjdk
Default locale: en_US, platform encoding: ANSI_X3.4-1968
OS name: "linux", version: "4.12.13-1-arch", arch: "amd64", family: "unix"
[DEBUG] Created new class realm maven.api
[DEBUG] Importing foreign packages into class realm maven.api
[DEBUG]   Imported: javax.enterprise.inject.* < plexus.core
[DEBUG]   Imported: javax.enterprise.util.* < plexus.core
[DEBUG]   Imported: javax.inject.* < plexus.core
[DEBUG]   Imported: org.apache.maven.* < plexus.core
[DEBUG]   Imported: org.apache.maven.artifact < plexus.core
[DEBUG]   Imported: org.apache.maven.classrealm < plexus.core
[DEBUG]   Imported: org.apache.maven.cli < plexus.core
[DEBUG]   Imported: org.apache.maven.configuration < plexus.core
[DEBUG]   Imported: org.apache.maven.exception < plexus.core
[DEBUG]   Imported: org.apache.maven.execution < plexus.core
[DEBUG]   Imported: org.apache.maven.execution.scope < plexus.core
[DEBUG]   Imported: org.apache.maven.lifecycle < plexus.core
[DEBUG]   Imported: org.apache.maven.model < plexus.core
[DEBUG]   Imported: org.apache.maven.monitor < plexus.core
[DEBUG]   Imported: org.apache.maven.plugin < plexus.core
[DEBUG]   Imported: org.apache.maven.profiles < plexus.core
[DEBUG]   Imported: org.apache.maven.project < plexus.core
[DEBUG]   Imported: org.apache.maven.reporting < plexus.core
[DEBUG]   Imported: org.apache.maven.repository < plexus.core
[DEBUG]   Imported: org.apache.maven.rtinfo < plexus.core
[DEBUG]   Imported: org.apache.maven.settings < plexus.core
[DEBUG]   Imported: org.apache.maven.toolchain < plexus.core
[DEBUG]   Imported: org.apache.maven.usability < plexus.core
[DEBUG]   Imported: org.apache.maven.wagon.* < plexus.core
[DEBUG]   Imported: org.apache.maven.wagon.authentication < plexus.core
[DEBUG]   Imported: org.apache.maven.wagon.authorization < plexus.core
[DEBUG]   Imported: org.apache.maven.wagon.events < plexus.core
[DEBUG]   Imported: org.apache.maven.wagon.observers < plexus.core
[DEBUG]   Imported: org.apache.maven.wagon.proxy < plexus.core
[DEBUG]   Imported: org.apache.maven.wagon.repository < plexus.core
[DEBUG]   Imported: org.apache.maven.wagon.resource < plexus.core
[DEBUG]   Imported: org.codehaus.classworlds < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.* < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.classworlds < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.component < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.configuration < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.container < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.context < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.lifecycle < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.logging < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.personality < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.util.xml.Xpp3Dom < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.util.xml.pull.XmlPullParser < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.util.xml.pull.XmlPullParserException < plexus.core
[DEBUG]   Imported: org.codehaus.plexus.util.xml.pull.XmlSerializer < plexus.core
[DEBUG]   Imported: org.eclipse.aether.* < plexus.core
[DEBUG]   Imported: org.eclipse.aether.artifact < plexus.core
[DEBUG]   Imported: org.eclipse.aether.collection < plexus.core
[DEBUG]   Imported: org.eclipse.aether.deployment < plexus.core
[DEBUG]   Imported: org.eclipse.aether.graph < plexus.core
[DEBUG]   Imported: org.eclipse.aether.impl < plexus.core
[DEBUG]   Imported: org.eclipse.aether.installation < plexus.core
[DEBUG]   Imported: org.eclipse.aether.internal.impl < plexus.core
[DEBUG]   Imported: org.eclipse.aether.metadata < plexus.core
[DEBUG]   Imported: org.eclipse.aether.repository < plexus.core
[DEBUG]   Imported: org.eclipse.aether.resolution < plexus.core
[DEBUG]   Imported: org.eclipse.aether.spi < plexus.core
[DEBUG]   Imported: org.eclipse.aether.transfer < plexus.core
[DEBUG]   Imported: org.eclipse.aether.version < plexus.core
[DEBUG]   Imported: org.fusesource.jansi.* < plexus.core
[DEBUG]   Imported: org.slf4j.* < plexus.core
[DEBUG]   Imported: org.slf4j.helpers.* < plexus.core
[DEBUG]   Imported: org.slf4j.spi.* < plexus.core
[DEBUG] Populating class realm maven.api
[INFO] Error stacktraces are turned on.
[DEBUG] Message scheme: color
[DEBUG] Message styles: debug info warning error success failure strong mojo project
[DEBUG] Reading global settings from /opt/maven/conf/settings.xml
[DEBUG] Reading user settings from /home/someone/.m2/settings.xml
[DEBUG] Reading global toolchains from /opt/maven/conf/toolchains.xml
[DEBUG] Reading user toolchains from /home/someone/.m2/toolchains.xml
[DEBUG] Using local repository at /home/someone/.m2/repository
[DEBUG] Using manager EnhancedLocalRepositoryManager with priority 10.0 for /home/someone/.m2/repository
[INFO] Scanning for projects...
[DEBUG] Extension realms for project com.io7m.bugs:maven-dependency-plugin-20171002:jar:0.0.1: (none)
[DEBUG] Looking up lifecycle mappings for packaging jar from ClassRealm[plexus.core, parent: null]
[DEBUG] === REACTOR BUILD PLAN ================================================
[DEBUG] Project: com.io7m.bugs:maven-dependency-plugin-20171002:jar:0.0.1
[DEBUG] Tasks:   [clean, verify]
[DEBUG] Style:   Regular
[DEBUG] =======================================================================
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] Building maven-dependency-plugin-20171002 0.0.1
[INFO] ------------------------------------------------------------------------
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] Lifecycle default -> [validate, initialize, generate-sources, process-sources, generate-resources, process-resources, compile, process-classes, generate-test-sources, process-test-sources, generate-test-resources, process-test-resources, test-compile, process-test-classes, test, prepare-package, package, pre-integration-test, integration-test, post-integration-test, verify, install, deploy]
[DEBUG] Lifecycle clean -> [pre-clean, clean, post-clean]
[DEBUG] Lifecycle site -> [pre-site, site, post-site, site-deploy]
[DEBUG] === PROJECT BUILD PLAN ================================================
[DEBUG] Project:       com.io7m.bugs:maven-dependency-plugin-20171002:0.0.1
[DEBUG] Dependencies (collect): []
[DEBUG] Dependencies (resolve): [compile, runtime, test]
[DEBUG] Repositories (dependencies): [sonatype-snapshots-repo (https://oss.sonatype.org/content/repositories/snapshots, default, snapshots), central (https://repo.maven.apache.org/maven2, default, releases)]
[DEBUG] Repositories (plugins)     : [central (https://repo.maven.apache.org/maven2, default, releases)]
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-clean-plugin:2.5:clean (default-clean)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <directory default-value="${project.build.directory}"/>
  <excludeDefaultDirectories default-value="false">${clean.excludeDefaultDirectories}</excludeDefaultDirectories>
  <failOnError default-value="true">${maven.clean.failOnError}</failOnError>
  <followSymLinks default-value="false">${clean.followSymLinks}</followSymLinks>
  <outputDirectory default-value="${project.build.outputDirectory}"/>
  <reportDirectory default-value="${project.reporting.outputDirectory}"/>
  <retryOnError default-value="true">${maven.clean.retryOnError}</retryOnError>
  <skip default-value="false">${clean.skip}</skip>
  <testOutputDirectory default-value="${project.build.testOutputDirectory}"/>
  <verbose>${clean.verbose}</verbose>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-resources-plugin:2.6:resources (default-resources)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <buildFilters default-value="${project.build.filters}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <escapeString>${maven.resources.escapeString}</escapeString>
  <escapeWindowsPaths default-value="true">${maven.resources.escapeWindowsPaths}</escapeWindowsPaths>
  <includeEmptyDirs default-value="false">${maven.resources.includeEmptyDirs}</includeEmptyDirs>
  <outputDirectory default-value="${project.build.outputDirectory}"/>
  <overwrite default-value="false">${maven.resources.overwrite}</overwrite>
  <project default-value="${project}"/>
  <resources default-value="${project.resources}"/>
  <session default-value="${session}"/>
  <supportMultiLineFiltering default-value="false">${maven.resources.supportMultiLineFiltering}</supportMultiLineFiltering>
  <useBuildFilters default-value="true"/>
  <useDefaultDelimiters default-value="true"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-compiler-plugin:3.7.0:compile (default-compile)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <basedir default-value="${basedir}"/>
  <buildDirectory default-value="${project.build.directory}"/>
  <compilePath default-value="${project.compileClasspathElements}"/>
  <compileSourceRoots default-value="${project.compileSourceRoots}"/>
  <compilerId default-value="javac">${maven.compiler.compilerId}</compilerId>
  <compilerReuseStrategy default-value="${reuseCreated}">${maven.compiler.compilerReuseStrategy}</compilerReuseStrategy>
  <compilerVersion>${maven.compiler.compilerVersion}</compilerVersion>
  <debug default-value="true">${maven.compiler.debug}</debug>
  <debuglevel>${maven.compiler.debuglevel}</debuglevel>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <executable>${maven.compiler.executable}</executable>
  <failOnError default-value="true">${maven.compiler.failOnError}</failOnError>
  <failOnWarning default-value="false">${maven.compiler.failOnWarning}</failOnWarning>
  <forceJavacCompilerUse default-value="false">${maven.compiler.forceJavacCompilerUse}</forceJavacCompilerUse>
  <fork default-value="false">${maven.compiler.fork}</fork>
  <generatedSourcesDirectory default-value="${project.build.directory}/generated-sources/annotations"/>
  <maxmem>${maven.compiler.maxmem}</maxmem>
  <meminitial>${maven.compiler.meminitial}</meminitial>
  <mojoExecution default-value="${mojoExecution}"/>
  <optimize default-value="false">${maven.compiler.optimize}</optimize>
  <outputDirectory default-value="${project.build.outputDirectory}"/>
  <parameters default-value="false">${maven.compiler.parameters}</parameters>
  <project default-value="${project}"/>
  <projectArtifact default-value="${project.artifact}"/>
  <release>9</release>
  <session default-value="${session}"/>
  <showDeprecation default-value="false">${maven.compiler.showDeprecation}</showDeprecation>
  <showWarnings default-value="false">${maven.compiler.showWarnings}</showWarnings>
  <skipMain>${maven.main.skip}</skipMain>
  <skipMultiThreadWarning default-value="false">${maven.compiler.skipMultiThreadWarning}</skipMultiThreadWarning>
  <source default-value="1.5">9</source>
  <staleMillis default-value="0">${lastModGranularityMs}</staleMillis>
  <target default-value="1.5">9</target>
  <useIncrementalCompilation default-value="true">${maven.compiler.useIncrementalCompilation}</useIncrementalCompilation>
  <verbose default-value="false">${maven.compiler.verbose}</verbose>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-resources-plugin:2.6:testResources (default-testResources)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <buildFilters default-value="${project.build.filters}"/>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <escapeString>${maven.resources.escapeString}</escapeString>
  <escapeWindowsPaths default-value="true">${maven.resources.escapeWindowsPaths}</escapeWindowsPaths>
  <includeEmptyDirs default-value="false">${maven.resources.includeEmptyDirs}</includeEmptyDirs>
  <outputDirectory default-value="${project.build.testOutputDirectory}"/>
  <overwrite default-value="false">${maven.resources.overwrite}</overwrite>
  <project default-value="${project}"/>
  <resources default-value="${project.testResources}"/>
  <session default-value="${session}"/>
  <skip>${maven.test.skip}</skip>
  <supportMultiLineFiltering default-value="false">${maven.resources.supportMultiLineFiltering}</supportMultiLineFiltering>
  <useBuildFilters default-value="true"/>
  <useDefaultDelimiters default-value="true"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-compiler-plugin:3.7.0:testCompile (default-testCompile)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <basedir default-value="${basedir}"/>
  <buildDirectory default-value="${project.build.directory}"/>
  <compilePath default-value="${project.compileClasspathElements}"/>
  <compileSourceRoots default-value="${project.testCompileSourceRoots}"/>
  <compilerId default-value="javac">${maven.compiler.compilerId}</compilerId>
  <compilerReuseStrategy default-value="${reuseCreated}">${maven.compiler.compilerReuseStrategy}</compilerReuseStrategy>
  <compilerVersion>${maven.compiler.compilerVersion}</compilerVersion>
  <debug default-value="true">${maven.compiler.debug}</debug>
  <debuglevel>${maven.compiler.debuglevel}</debuglevel>
  <encoding default-value="${project.build.sourceEncoding}">${encoding}</encoding>
  <executable>${maven.compiler.executable}</executable>
  <failOnError default-value="true">${maven.compiler.failOnError}</failOnError>
  <failOnWarning default-value="false">${maven.compiler.failOnWarning}</failOnWarning>
  <forceJavacCompilerUse default-value="false">${maven.compiler.forceJavacCompilerUse}</forceJavacCompilerUse>
  <fork default-value="false">${maven.compiler.fork}</fork>
  <generatedTestSourcesDirectory default-value="${project.build.directory}/generated-test-sources/test-annotations"/>
  <maxmem>${maven.compiler.maxmem}</maxmem>
  <meminitial>${maven.compiler.meminitial}</meminitial>
  <mojoExecution default-value="${mojoExecution}"/>
  <optimize default-value="false">${maven.compiler.optimize}</optimize>
  <outputDirectory default-value="${project.build.testOutputDirectory}"/>
  <parameters default-value="false">${maven.compiler.parameters}</parameters>
  <project default-value="${project}"/>
  <release>9</release>
  <session default-value="${session}"/>
  <showDeprecation default-value="false">${maven.compiler.showDeprecation}</showDeprecation>
  <showWarnings default-value="false">${maven.compiler.showWarnings}</showWarnings>
  <skip>${maven.test.skip}</skip>
  <skipMultiThreadWarning default-value="false">${maven.compiler.skipMultiThreadWarning}</skipMultiThreadWarning>
  <source default-value="1.5">9</source>
  <staleMillis default-value="0">${lastModGranularityMs}</staleMillis>
  <target default-value="1.5">9</target>
  <testPath default-value="${project.testClasspathElements}"/>
  <testRelease>${maven.compiler.testRelease}</testRelease>
  <testSource>${maven.compiler.testSource}</testSource>
  <testTarget>${maven.compiler.testTarget}</testTarget>
  <useIncrementalCompilation default-value="true">${maven.compiler.useIncrementalCompilation}</useIncrementalCompilation>
  <verbose default-value="false">${maven.compiler.verbose}</verbose>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-surefire-plugin:2.12.4:test (default-test)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <argLine>${argLine}</argLine>
  <basedir default-value="${basedir}"/>
  <childDelegation default-value="false">${childDelegation}</childDelegation>
  <classesDirectory default-value="${project.build.outputDirectory}"/>
  <debugForkedProcess>${maven.surefire.debug}</debugForkedProcess>
  <disableXmlReport default-value="false">${disableXmlReport}</disableXmlReport>
  <enableAssertions default-value="true">${enableAssertions}</enableAssertions>
  <excludedGroups>${excludedGroups}</excludedGroups>
  <failIfNoSpecifiedTests>${surefire.failIfNoSpecifiedTests}</failIfNoSpecifiedTests>
  <failIfNoTests>${failIfNoTests}</failIfNoTests>
  <forkMode default-value="once">${forkMode}</forkMode>
  <forkedProcessTimeoutInSeconds>${surefire.timeout}</forkedProcessTimeoutInSeconds>
  <groups>${groups}</groups>
  <junitArtifactName default-value="junit:junit">${junitArtifactName}</junitArtifactName>
  <jvm>${jvm}</jvm>
  <localRepository default-value="${localRepository}"/>
  <objectFactory>${objectFactory}</objectFactory>
  <parallel>${parallel}</parallel>
  <parallelMavenExecution default-value="${session.parallel}"/>
  <perCoreThreadCount default-value="true">${perCoreThreadCount}</perCoreThreadCount>
  <pluginArtifactMap>${plugin.artifactMap}</pluginArtifactMap>
  <pluginDescriptor default-value="${plugin}"/>
  <printSummary default-value="true">${surefire.printSummary}</printSummary>
  <projectArtifactMap>${project.artifactMap}</projectArtifactMap>
  <redirectTestOutputToFile default-value="false">${maven.test.redirectTestOutputToFile}</redirectTestOutputToFile>
  <remoteRepositories default-value="${project.pluginArtifactRepositories}"/>
  <reportFormat default-value="brief">${surefire.reportFormat}</reportFormat>
  <reportNameSuffix default-value="">${surefire.reportNameSuffix}</reportNameSuffix>
  <reportsDirectory default-value="${project.build.directory}/surefire-reports"/>
  <runOrder default-value="filesystem"/>
  <skip default-value="false">${maven.test.skip}</skip>
  <skipExec>${maven.test.skip.exec}</skipExec>
  <skipTests default-value="false">${skipTests}</skipTests>
  <test>${test}</test>
  <testClassesDirectory default-value="${project.build.testOutputDirectory}"/>
  <testFailureIgnore default-value="false">${maven.test.failure.ignore}</testFailureIgnore>
  <testNGArtifactName default-value="org.testng:testng">${testNGArtifactName}</testNGArtifactName>
  <testSourceDirectory default-value="${project.build.testSourceDirectory}"/>
  <threadCount>${threadCount}</threadCount>
  <trimStackTrace default-value="true">${trimStackTrace}</trimStackTrace>
  <useFile default-value="true">${surefire.useFile}</useFile>
  <useManifestOnlyJar default-value="true">${surefire.useManifestOnlyJar}</useManifestOnlyJar>
  <useSystemClassLoader default-value="true">${surefire.useSystemClassLoader}</useSystemClassLoader>
  <useUnlimitedThreads default-value="false">${useUnlimitedThreads}</useUnlimitedThreads>
  <workingDirectory>${basedir}</workingDirectory>
  <project default-value="${project}"/>
  <session default-value="${session}"/>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-jar-plugin:2.4:jar (default-jar)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <classesDirectory default-value="${project.build.outputDirectory}"/>
  <defaultManifestFile default-value="${project.build.outputDirectory}/META-INF/MANIFEST.MF"/>
  <finalName default-value="${project.build.finalName}">${jar.finalName}</finalName>
  <forceCreation default-value="false">${jar.forceCreation}</forceCreation>
  <outputDirectory default-value="${project.build.directory}"/>
  <project default-value="${project}"/>
  <session default-value="${session}"/>
  <skipIfEmpty default-value="false">${jar.skipIfEmpty}</skipIfEmpty>
  <useDefaultManifestFile default-value="false">${jar.useDefaultManifestFile}</useDefaultManifestFile>
</configuration>
[DEBUG] -----------------------------------------------------------------------
[DEBUG] Goal:          org.apache.maven.plugins:maven-dependency-plugin:3.0.2:analyze-only (analyze)
[DEBUG] Style:         Regular
[DEBUG] Configuration: <?xml version="1.0" encoding="UTF-8"?>
<configuration>
  <analyzer default-value="default">${analyzer}</analyzer>
  <baseDir default-value="${basedir}"/>
  <failOnWarning default-value="false">true</failOnWarning>
  <ignoreNonCompile default-value="false">${ignoreNonCompile}</ignoreNonCompile>
  <outputDirectory default-value="${project.build.directory}"/>
  <outputXML default-value="false">${outputXML}</outputXML>
  <project default-value="${project}"/>
  <scriptableFlag default-value="$$$%%%">${scriptableFlag}</scriptableFlag>
  <scriptableOutput default-value="false">${scriptableOutput}</scriptableOutput>
  <skip default-value="false">${mdep.analyze.skip}</skip>
  <verbose default-value="false">${verbose}</verbose>
</configuration>
[DEBUG] =======================================================================
[DEBUG] Dependency collection stats: {ConflictMarker.analyzeTime=0, ConflictMarker.markTime=1, ConflictMarker.nodeCount=1, ConflictIdSorter.graphTime=0, ConflictIdSorter.topsortTime=1, ConflictIdSorter.conflictIdCount=0, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=3, ConflictResolver.conflictItemCount=0, DefaultDependencyCollector.collectTime=1, DefaultDependencyCollector.transformTime=8}
[DEBUG] com.io7m.bugs:maven-dependency-plugin-20171002:jar:0.0.1
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ maven-dependency-plugin-20171002 ---
[DEBUG] Dependency collection stats: {ConflictMarker.analyzeTime=1, ConflictMarker.markTime=0, ConflictMarker.nodeCount=3, ConflictIdSorter.graphTime=0, ConflictIdSorter.topsortTime=0, ConflictIdSorter.conflictIdCount=3, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=3, ConflictResolver.conflictItemCount=3, DefaultDependencyCollector.collectTime=44, DefaultDependencyCollector.transformTime=4}
[DEBUG] org.apache.maven.plugins:maven-clean-plugin:jar:2.5:
[DEBUG]    org.apache.maven:maven-plugin-api:jar:2.0.6:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:3.0:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-clean-plugin:2.5
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-clean-plugin:2.5
[DEBUG]   Imported:  < maven.api
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-clean-plugin:2.5
[DEBUG]   Included: org.apache.maven.plugins:maven-clean-plugin:jar:2.5
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:3.0
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-clean-plugin:2.5:clean from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-clean-plugin:2.5, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@1b9e1916]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-clean-plugin:2.5:clean' with basic configurator -->
[DEBUG]   (f) directory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target
[DEBUG]   (f) excludeDefaultDirectories = false
[DEBUG]   (f) failOnError = true
[DEBUG]   (f) followSymLinks = false
[DEBUG]   (f) outputDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes
[DEBUG]   (f) reportDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/site
[DEBUG]   (f) retryOnError = true
[DEBUG]   (f) skip = false
[DEBUG]   (f) testOutputDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/test-classes
[DEBUG] -- end configuration --
[INFO] Deleting /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target
[INFO] Deleting file /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-dependency-plugin-20171002-0.0.1.jar
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/generated-sources/annotations
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/generated-sources
[INFO] Deleting file /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-archiver/pom.properties
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-archiver
[INFO] Deleting file /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes/com/io7m/example/Main.class
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes/com/io7m/example
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes/com/io7m
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes/com
[INFO] Deleting file /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes/module-info.class
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes
[INFO] Deleting file /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-status/maven-compiler-plugin/compile/default-compile/createdFiles.lst
[INFO] Deleting file /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-status/maven-compiler-plugin/compile/default-compile/inputFiles.lst
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-status/maven-compiler-plugin/compile/default-compile
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-status/maven-compiler-plugin/compile
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-status/maven-compiler-plugin
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-status
[INFO] Deleting directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target
[DEBUG] Skipping non-existing directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes
[DEBUG] Skipping non-existing directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/test-classes
[DEBUG] Skipping non-existing directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/site
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ maven-dependency-plugin-20171002 ---
[DEBUG] Dependency collection stats: {ConflictMarker.analyzeTime=1, ConflictMarker.markTime=0, ConflictMarker.nodeCount=77, ConflictIdSorter.graphTime=0, ConflictIdSorter.topsortTime=1, ConflictIdSorter.conflictIdCount=26, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=5, ConflictResolver.conflictItemCount=74, DefaultDependencyCollector.collectTime=164, DefaultDependencyCollector.transformTime=7}
[DEBUG] org.apache.maven.plugins:maven-resources-plugin:jar:2.6:
[DEBUG]    org.apache.maven:maven-plugin-api:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-project:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-profile:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-artifact-manager:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-plugin-registry:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-core:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-plugin-parameter-documenter:jar:2.0.6:compile
[DEBUG]       org.apache.maven.reporting:maven-reporting-api:jar:2.0.6:compile
[DEBUG]          org.apache.maven.doxia:doxia-sink-api:jar:1.0-alpha-7:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-error-diagnostics:jar:2.0.6:compile
[DEBUG]       commons-cli:commons-cli:jar:1.0:compile
[DEBUG]       org.apache.maven:maven-plugin-descriptor:jar:2.0.6:compile
[DEBUG]       org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4:compile
[DEBUG]       classworlds:classworlds:jar:1.1:compile
[DEBUG]    org.apache.maven:maven-artifact:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-settings:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-model:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-monitor:jar:2.0.6:compile
[DEBUG]    org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9-stable-1:compile
[DEBUG]       junit:junit:jar:3.8.1:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:2.0.5:compile
[DEBUG]    org.apache.maven.shared:maven-filtering:jar:1.1:compile
[DEBUG]       org.sonatype.plexus:plexus-build-api:jar:0.0.4:compile
[DEBUG]    org.codehaus.plexus:plexus-interpolation:jar:1.13:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-resources-plugin:2.6
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-resources-plugin:2.6
[DEBUG]   Imported:  < maven.api
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-resources-plugin:2.6
[DEBUG]   Included: org.apache.maven.plugins:maven-resources-plugin:jar:2.6
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-api:jar:2.0.6
[DEBUG]   Included: org.apache.maven.doxia:doxia-sink-api:jar:1.0-alpha-7
[DEBUG]   Included: commons-cli:commons-cli:jar:1.0
[DEBUG]   Included: org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4
[DEBUG]   Included: junit:junit:jar:3.8.1
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:2.0.5
[DEBUG]   Included: org.apache.maven.shared:maven-filtering:jar:1.1
[DEBUG]   Included: org.sonatype.plexus:plexus-build-api:jar:0.0.4
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.13
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-resources-plugin:2.6:resources from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-resources-plugin:2.6, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@1b9e1916]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-resources-plugin:2.6:resources' with basic configurator -->
[DEBUG]   (f) buildFilters = []
[DEBUG]   (f) escapeWindowsPaths = true
[DEBUG]   (s) includeEmptyDirs = false
[DEBUG]   (s) outputDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes
[DEBUG]   (s) overwrite = false
[DEBUG]   (f) project = MavenProject: com.io7m.bugs:maven-dependency-plugin-20171002:0.0.1 @ /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/pom.xml
[DEBUG]   (s) resources = [Resource {targetPath: null, filtering: false, FileSet {directory: /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/resources, PatternSet [includes: {}, excludes: {}]}}]
[DEBUG]   (f) session = org.apache.maven.execution.MavenSession@cfbc8e8
[DEBUG]   (f) supportMultiLineFiltering = false
[DEBUG]   (f) useBuildFilters = true
[DEBUG]   (s) useDefaultDelimiters = true
[DEBUG] -- end configuration --
[DEBUG] properties used {awt.toolkit=sun.awt.X11.XToolkit, java.specification.version=9, sun.cpu.isalist=, sun.jnu.encoding=ANSI_X3.4-1968, sun.arch.data.model=64, java.vendor.url=http://java.oracle.com/, sun.boot.library.path=/usr/lib/jvm/java-9-openjdk/lib, maven.build.version=Apache Maven 3.5.0 (NON-CANONICAL_2017-04-10T13:56:20+03:00_root; 2017-04-10T10:56:20Z), sun.java.command=org.codehaus.plexus.classworlds.launcher.Launcher -X clean verify, jdk.debug=release, maven.home=/opt/maven, maven.version=3.5.0, java.specification.vendor=Oracle Corporation, env.JAVA_HOME=/usr/lib/jvm/default, java.home=/usr/lib/jvm/java-9-openjdk, file.separator=/, java.vm.compressedOopsMode=32-bit, line.separator=
, java.specification.name=Java Platform API Specification, java.vm.specification.vendor=Oracle Corporation, lwjgl.deployment=true, sun.management.compiler=HotSpot 64-Bit Tiered Compilers, java.runtime.version=9+181, user.name=someone, file.encoding=ANSI_X3.4-1968, env.SHLVL=0, java.io.tmpdir=/tmp, java.version=9, java.vm.specification.name=Java Virtual Machine Specification, java.awt.printerjob=sun.print.PSPrinterJob, sun.os.patch.level=unknown, org.slf4j.simpleLogger.defaultLogLevel=debug, java.library.path=/usr/java/packages/lib:/usr/lib64:/lib64:/lib:/usr/lib, java.vendor=Oracle Corporation, classworlds.conf=/opt/maven/bin/m2.conf, sun.io.unicode.encoding=UnicodeLittle, library.jansi.path=/opt/maven/lib/jansi-native/linux64, immutables.deployment=true, env.OLDPWD=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, env.PWD=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, file.encoding.pkg=sun.io, java.class.path=/opt/maven/boot/plexus-classworlds-2.5.2.jar, java.vm.vendor=Oracle Corporation, gpg.keyname=io7m.com (2017 release-signing), io7m.deployment=true, user.timezone=UTC, maven.conf=/opt/maven/conf, os.name=Linux, java.vm.specification.version=9, sun.java.launcher=SUN_STANDARD, user.country=US, sun.cpu.endian=little, user.home=/home/someone, user.language=en, java.awt.graphicsenv=sun.awt.X11GraphicsEnvironment, gpg.useagent=true, path.separator=:, os.version=4.12.13-1-ARCH, java.runtime.name=OpenJDK Runtime Environment, java.vm.name=OpenJDK 64-Bit Server VM, env.MAVEN_CMD_LINE_ARGS= -X clean verify, java.vendor.url.bug=http://bugreport.java.com/bugreport/, user.dir=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, os.arch=amd64, maven.multiModuleProjectDirectory=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, env.MAVEN_PROJECTBASEDIR=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, java.vm.info=mixed mode, java.vm.version=9+181, java.class.version=53.0}
[WARNING] Using platform encoding (ANSI_X3.4-1968 actually) to copy filtered resources, i.e. build is platform dependent!
[DEBUG] resource with targetPath null
directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/resources
excludes []
includes []
[INFO] skip non existing resourceDirectory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/resources
[DEBUG] no use filter components
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ maven-dependency-plugin-20171002 ---
[DEBUG] Dependency collection stats: {ConflictMarker.analyzeTime=1, ConflictMarker.markTime=0, ConflictMarker.nodeCount=118, ConflictIdSorter.graphTime=0, ConflictIdSorter.topsortTime=1, ConflictIdSorter.conflictIdCount=45, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=4, ConflictResolver.conflictItemCount=72, DefaultDependencyCollector.collectTime=393, DefaultDependencyCollector.transformTime=6}
[DEBUG] org.apache.maven.plugins:maven-compiler-plugin:jar:3.7.0:
[DEBUG]    org.apache.maven:maven-plugin-api:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model:jar:3.0:compile
[DEBUG]       org.sonatype.sisu:sisu-inject-plexus:jar:1.4.2:compile
[DEBUG]          org.sonatype.sisu:sisu-inject-bean:jar:1.4.2:compile
[DEBUG]             org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7:compile
[DEBUG]    org.apache.maven:maven-artifact:jar:3.0:compile
[DEBUG]       org.codehaus.plexus:plexus-utils:jar:2.0.4:compile
[DEBUG]    org.apache.maven:maven-core:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-aether-provider:jar:3.0:runtime
[DEBUG]       org.sonatype.aether:aether-impl:jar:1.7:compile
[DEBUG]          org.sonatype.aether:aether-spi:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-api:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-util:jar:1.7:compile
[DEBUG]       org.codehaus.plexus:plexus-interpolation:jar:1.14:compile
[DEBUG]       org.codehaus.plexus:plexus-classworlds:jar:2.2.3:compile
[DEBUG]       org.codehaus.plexus:plexus-component-annotations:jar:1.6:compile
[DEBUG]       org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3:compile
[DEBUG]          org.sonatype.plexus:plexus-cipher:jar:1.4:compile
[DEBUG]    org.apache.maven.shared:maven-shared-utils:jar:3.1.0:compile
[DEBUG]       commons-io:commons-io:jar:2.5:compile
[DEBUG]    org.apache.maven.shared:maven-shared-incremental:jar:1.1:compile
[DEBUG]    org.codehaus.plexus:plexus-java:jar:0.9.2:compile
[DEBUG]       org.ow2.asm:asm:jar:6.0_BETA:compile
[DEBUG]       com.thoughtworks.qdox:qdox:jar:2.0-M7:compile
[DEBUG]    org.codehaus.plexus:plexus-compiler-api:jar:2.8.2:compile
[DEBUG]    org.codehaus.plexus:plexus-compiler-manager:jar:2.8.2:compile
[DEBUG]    org.codehaus.plexus:plexus-compiler-javac:jar:2.8.2:runtime
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-compiler-plugin:3.7.0
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-compiler-plugin:3.7.0
[DEBUG]   Imported:  < maven.api
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-compiler-plugin:3.7.0
[DEBUG]   Included: org.apache.maven.plugins:maven-compiler-plugin:jar:3.7.0
[DEBUG]   Included: org.sonatype.sisu:sisu-inject-bean:jar:1.4.2
[DEBUG]   Included: org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:2.0.4
[DEBUG]   Included: org.apache.maven:maven-aether-provider:jar:3.0
[DEBUG]   Included: org.sonatype.aether:aether-util:jar:1.7
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.14
[DEBUG]   Included: org.codehaus.plexus:plexus-component-annotations:jar:1.6
[DEBUG]   Included: org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3
[DEBUG]   Included: org.sonatype.plexus:plexus-cipher:jar:1.4
[DEBUG]   Included: org.apache.maven.shared:maven-shared-utils:jar:3.1.0
[DEBUG]   Included: commons-io:commons-io:jar:2.5
[DEBUG]   Included: org.apache.maven.shared:maven-shared-incremental:jar:1.1
[DEBUG]   Included: org.codehaus.plexus:plexus-java:jar:0.9.2
[DEBUG]   Included: org.ow2.asm:asm:jar:6.0_BETA
[DEBUG]   Included: com.thoughtworks.qdox:qdox:jar:2.0-M7
[DEBUG]   Included: org.codehaus.plexus:plexus-compiler-api:jar:2.8.2
[DEBUG]   Included: org.codehaus.plexus:plexus-compiler-manager:jar:2.8.2
[DEBUG]   Included: org.codehaus.plexus:plexus-compiler-javac:jar:2.8.2
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-compiler-plugin:3.7.0:compile from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-compiler-plugin:3.7.0, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@1b9e1916]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-compiler-plugin:3.7.0:compile' with basic configurator -->
[DEBUG]   (f) basedir = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002
[DEBUG]   (f) buildDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target
[DEBUG]   (f) compilePath = [/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes]
[DEBUG]   (f) compileSourceRoots = [/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/java]
[DEBUG]   (f) compilerId = javac
[DEBUG]   (f) debug = true
[DEBUG]   (f) failOnError = true
[DEBUG]   (f) failOnWarning = false
[DEBUG]   (f) forceJavacCompilerUse = false
[DEBUG]   (f) fork = false
[DEBUG]   (f) generatedSourcesDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/generated-sources/annotations
[DEBUG]   (f) mojoExecution = org.apache.maven.plugins:maven-compiler-plugin:3.7.0:compile {execution: default-compile}
[DEBUG]   (f) optimize = false
[DEBUG]   (f) outputDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes
[DEBUG]   (f) parameters = false
[DEBUG]   (f) project = MavenProject: com.io7m.bugs:maven-dependency-plugin-20171002:0.0.1 @ /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/pom.xml
[DEBUG]   (f) projectArtifact = com.io7m.bugs:maven-dependency-plugin-20171002:jar:0.0.1
[DEBUG]   (f) release = 9
[DEBUG]   (f) session = org.apache.maven.execution.MavenSession@cfbc8e8
[DEBUG]   (f) showDeprecation = false
[DEBUG]   (f) showWarnings = false
[DEBUG]   (f) skipMultiThreadWarning = false
[DEBUG]   (f) source = 9
[DEBUG]   (f) staleMillis = 0
[DEBUG]   (f) target = 9
[DEBUG]   (f) useIncrementalCompilation = true
[DEBUG]   (f) verbose = false
[DEBUG] -- end configuration --
[DEBUG] Using compiler 'javac'.
[DEBUG] Adding /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/generated-sources/annotations to compile source roots:
  /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/java
[DEBUG] New compile source roots:
  /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/java
  /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/generated-sources/annotations
[DEBUG] CompilerReuseStrategy: reuseCreated
[DEBUG] useIncrementalCompilation enabled
[DEBUG] Stale source detected: /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/java/module-info.java
[DEBUG] Stale source detected: /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/java/com/io7m/example/Main.java
[DEBUG] Stale source detected: /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/java/com/io7m/example/package-info.java
[INFO] Changes detected - recompiling the module!
[DEBUG] Classpath:
[DEBUG]  /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes
[DEBUG] Source roots:
[DEBUG]  /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/java
[DEBUG]  /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/generated-sources/annotations
[DEBUG] Command line options:
[DEBUG] -d /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes -classpath /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes: -sourcepath /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/main/java:/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/generated-sources/annotations: -s /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/generated-sources/annotations -g -nowarn --release 9
[WARNING] File encoding has not been set, using platform encoding ANSI_X3.4-1968, i.e. build is platform dependent!
[DEBUG] incrementalBuildHelper#beforeRebuildExecution
[INFO] Compiling 3 source files to /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes
[DEBUG] incrementalBuildHelper#afterRebuildExecution
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ maven-dependency-plugin-20171002 ---
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-resources-plugin:2.6:testResources from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-resources-plugin:2.6, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@1b9e1916]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-resources-plugin:2.6:testResources' with basic configurator -->
[DEBUG]   (f) buildFilters = []
[DEBUG]   (f) escapeWindowsPaths = true
[DEBUG]   (s) includeEmptyDirs = false
[DEBUG]   (s) outputDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/test-classes
[DEBUG]   (s) overwrite = false
[DEBUG]   (f) project = MavenProject: com.io7m.bugs:maven-dependency-plugin-20171002:0.0.1 @ /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/pom.xml
[DEBUG]   (s) resources = [Resource {targetPath: null, filtering: false, FileSet {directory: /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/test/resources, PatternSet [includes: {}, excludes: {}]}}]
[DEBUG]   (f) session = org.apache.maven.execution.MavenSession@cfbc8e8
[DEBUG]   (f) supportMultiLineFiltering = false
[DEBUG]   (f) useBuildFilters = true
[DEBUG]   (s) useDefaultDelimiters = true
[DEBUG] -- end configuration --
[DEBUG] properties used {awt.toolkit=sun.awt.X11.XToolkit, java.specification.version=9, sun.cpu.isalist=, sun.jnu.encoding=ANSI_X3.4-1968, sun.arch.data.model=64, java.vendor.url=http://java.oracle.com/, sun.boot.library.path=/usr/lib/jvm/java-9-openjdk/lib, maven.build.version=Apache Maven 3.5.0 (NON-CANONICAL_2017-04-10T13:56:20+03:00_root; 2017-04-10T10:56:20Z), sun.java.command=org.codehaus.plexus.classworlds.launcher.Launcher -X clean verify, jdk.debug=release, maven.home=/opt/maven, maven.version=3.5.0, java.specification.vendor=Oracle Corporation, env.JAVA_HOME=/usr/lib/jvm/default, java.home=/usr/lib/jvm/java-9-openjdk, file.separator=/, java.vm.compressedOopsMode=32-bit, line.separator=
, java.specification.name=Java Platform API Specification, java.vm.specification.vendor=Oracle Corporation, lwjgl.deployment=true, sun.management.compiler=HotSpot 64-Bit Tiered Compilers, java.runtime.version=9+181, user.name=someone, file.encoding=ANSI_X3.4-1968, env.SHLVL=0, java.io.tmpdir=/tmp, java.version=9, java.vm.specification.name=Java Virtual Machine Specification, java.awt.printerjob=sun.print.PSPrinterJob, sun.os.patch.level=unknown, org.slf4j.simpleLogger.defaultLogLevel=debug, java.library.path=/usr/java/packages/lib:/usr/lib64:/lib64:/lib:/usr/lib, java.vendor=Oracle Corporation, classworlds.conf=/opt/maven/bin/m2.conf, sun.io.unicode.encoding=UnicodeLittle, library.jansi.path=/opt/maven/lib/jansi-native/linux64, immutables.deployment=true, env.OLDPWD=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, env.PWD=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, file.encoding.pkg=sun.io, java.class.path=/opt/maven/boot/plexus-classworlds-2.5.2.jar, java.vm.vendor=Oracle Corporation, gpg.keyname=io7m.com (2017 release-signing), io7m.deployment=true, user.timezone=UTC, maven.conf=/opt/maven/conf, os.name=Linux, java.vm.specification.version=9, sun.java.launcher=SUN_STANDARD, user.country=US, sun.cpu.endian=little, user.home=/home/someone, user.language=en, java.awt.graphicsenv=sun.awt.X11GraphicsEnvironment, gpg.useagent=true, path.separator=:, os.version=4.12.13-1-ARCH, java.runtime.name=OpenJDK Runtime Environment, java.vm.name=OpenJDK 64-Bit Server VM, env.MAVEN_CMD_LINE_ARGS= -X clean verify, java.vendor.url.bug=http://bugreport.java.com/bugreport/, user.dir=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, os.arch=amd64, maven.multiModuleProjectDirectory=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, env.MAVEN_PROJECTBASEDIR=/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002, java.vm.info=mixed mode, java.vm.version=9+181, java.class.version=53.0}
[WARNING] Using platform encoding (ANSI_X3.4-1968 actually) to copy filtered resources, i.e. build is platform dependent!
[DEBUG] resource with targetPath null
directory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/test/resources
excludes []
includes []
[INFO] skip non existing resourceDirectory /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/test/resources
[DEBUG] no use filter components
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ maven-dependency-plugin-20171002 ---
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-compiler-plugin:3.7.0:testCompile from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-compiler-plugin:3.7.0, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@1b9e1916]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-compiler-plugin:3.7.0:testCompile' with basic configurator -->
[DEBUG]   (f) basedir = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002
[DEBUG]   (f) buildDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target
[DEBUG]   (f) compilePath = [/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes]
[DEBUG]   (f) compileSourceRoots = [/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/test/java]
[DEBUG]   (f) compilerId = javac
[DEBUG]   (f) debug = true
[DEBUG]   (f) failOnError = true
[DEBUG]   (f) failOnWarning = false
[DEBUG]   (f) forceJavacCompilerUse = false
[DEBUG]   (f) fork = false
[DEBUG]   (f) generatedTestSourcesDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/generated-test-sources/test-annotations
[DEBUG]   (f) mojoExecution = org.apache.maven.plugins:maven-compiler-plugin:3.7.0:testCompile {execution: default-testCompile}
[DEBUG]   (f) optimize = false
[DEBUG]   (f) outputDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/test-classes
[DEBUG]   (f) parameters = false
[DEBUG]   (f) project = MavenProject: com.io7m.bugs:maven-dependency-plugin-20171002:0.0.1 @ /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/pom.xml
[DEBUG]   (f) release = 9
[DEBUG]   (f) session = org.apache.maven.execution.MavenSession@cfbc8e8
[DEBUG]   (f) showDeprecation = false
[DEBUG]   (f) showWarnings = false
[DEBUG]   (f) skipMultiThreadWarning = false
[DEBUG]   (f) source = 9
[DEBUG]   (f) staleMillis = 0
[DEBUG]   (f) target = 9
[DEBUG]   (f) testPath = [/home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/test-classes, /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes]
[DEBUG]   (f) useIncrementalCompilation = true
[DEBUG]   (f) verbose = false
[DEBUG] -- end configuration --
[DEBUG] Using compiler 'javac'.
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ maven-dependency-plugin-20171002 ---
[DEBUG] Dependency collection stats: {ConflictMarker.analyzeTime=1, ConflictMarker.markTime=1, ConflictMarker.nodeCount=132, ConflictIdSorter.graphTime=0, ConflictIdSorter.topsortTime=0, ConflictIdSorter.conflictIdCount=27, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=2, ConflictResolver.conflictItemCount=77, DefaultDependencyCollector.collectTime=134, DefaultDependencyCollector.transformTime=4}
[DEBUG] org.apache.maven.plugins:maven-surefire-plugin:jar:2.12.4:
[DEBUG]    org.apache.maven:maven-plugin-api:jar:2.0.9:compile
[DEBUG]    org.apache.maven.surefire:surefire-booter:jar:2.12.4:compile
[DEBUG]       org.apache.maven.surefire:surefire-api:jar:2.12.4:compile
[DEBUG]    org.apache.maven.surefire:maven-surefire-common:jar:2.12.4:compile
[DEBUG]       org.apache.commons:commons-lang3:jar:3.1:compile
[DEBUG]       org.apache.maven.shared:maven-common-artifact-filters:jar:1.3:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:3.0.8:compile
[DEBUG]    org.apache.maven:maven-artifact:jar:2.0.9:compile
[DEBUG]    org.apache.maven:maven-project:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-settings:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-profile:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-model:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-artifact-manager:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-plugin-registry:jar:2.0.9:compile
[DEBUG]       org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9-stable-1:compile
[DEBUG]          junit:junit:jar:3.8.1:test
[DEBUG]    org.apache.maven:maven-core:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-plugin-parameter-documenter:jar:2.0.9:compile
[DEBUG]       org.apache.maven.reporting:maven-reporting-api:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-repository-metadata:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-error-diagnostics:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-plugin-descriptor:jar:2.0.9:compile
[DEBUG]       org.apache.maven:maven-monitor:jar:2.0.9:compile
[DEBUG]       classworlds:classworlds:jar:1.1:compile
[DEBUG]    org.apache.maven:maven-toolchain:jar:2.0.9:compile
[DEBUG]    org.apache.maven.plugin-tools:maven-plugin-annotations:jar:3.1:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-surefire-plugin:2.12.4
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-surefire-plugin:2.12.4
[DEBUG]   Imported:  < maven.api
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-surefire-plugin:2.12.4
[DEBUG]   Included: org.apache.maven.plugins:maven-surefire-plugin:jar:2.12.4
[DEBUG]   Included: org.apache.maven.surefire:surefire-booter:jar:2.12.4
[DEBUG]   Included: org.apache.maven.surefire:surefire-api:jar:2.12.4
[DEBUG]   Included: org.apache.maven.surefire:maven-surefire-common:jar:2.12.4
[DEBUG]   Included: org.apache.commons:commons-lang3:jar:3.1
[DEBUG]   Included: org.apache.maven.shared:maven-common-artifact-filters:jar:1.3
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:3.0.8
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-api:jar:2.0.9
[DEBUG]   Included: org.apache.maven.plugin-tools:maven-plugin-annotations:jar:3.1
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-surefire-plugin:2.12.4:test from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-surefire-plugin:2.12.4, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@1b9e1916]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-surefire-plugin:2.12.4:test' with basic configurator -->
[DEBUG]   (s) basedir = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002
[DEBUG]   (s) childDelegation = false
[DEBUG]   (s) classesDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes
[DEBUG]   (s) disableXmlReport = false
[DEBUG]   (s) enableAssertions = true
[DEBUG]   (s) forkMode = once
[DEBUG]   (s) junitArtifactName = junit:junit
[DEBUG]   (s) localRepository =       id: local
      url: file:///home/someone/.m2/repository/
   layout: default
snapshots: [enabled => true, update => always]
 releases: [enabled => true, update => always]

[DEBUG]   (f) parallelMavenExecution = false
[DEBUG]   (s) perCoreThreadCount = true
[DEBUG]   (s) pluginArtifactMap = {org.apache.maven.plugins:maven-surefire-plugin=org.apache.maven.plugins:maven-surefire-plugin:maven-plugin:2.12.4:, org.apache.maven:maven-plugin-api=org.apache.maven:maven-plugin-api:jar:2.0.9:compile, org.apache.maven.surefire:surefire-booter=org.apache.maven.surefire:surefire-booter:jar:2.12.4:compile, org.apache.maven.surefire:surefire-api=org.apache.maven.surefire:surefire-api:jar:2.12.4:compile, org.apache.maven.surefire:maven-surefire-common=org.apache.maven.surefire:maven-surefire-common:jar:2.12.4:compile, org.apache.commons:commons-lang3=org.apache.commons:commons-lang3:jar:3.1:compile, org.apache.maven.shared:maven-common-artifact-filters=org.apache.maven.shared:maven-common-artifact-filters:jar:1.3:compile, org.codehaus.plexus:plexus-utils=org.codehaus.plexus:plexus-utils:jar:3.0.8:compile, org.apache.maven:maven-artifact=org.apache.maven:maven-artifact:jar:2.0.9:compile, org.apache.maven:maven-project=org.apache.maven:maven-project:jar:2.0.9:compile, org.apache.maven:maven-settings=org.apache.maven:maven-settings:jar:2.0.9:compile, org.apache.maven:maven-profile=org.apache.maven:maven-profile:jar:2.0.9:compile, org.apache.maven:maven-model=org.apache.maven:maven-model:jar:2.0.9:compile, org.apache.maven:maven-artifact-manager=org.apache.maven:maven-artifact-manager:jar:2.0.9:compile, org.apache.maven:maven-plugin-registry=org.apache.maven:maven-plugin-registry:jar:2.0.9:compile, org.codehaus.plexus:plexus-container-default=org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9-stable-1:compile, org.apache.maven:maven-core=org.apache.maven:maven-core:jar:2.0.9:compile, org.apache.maven:maven-plugin-parameter-documenter=org.apache.maven:maven-plugin-parameter-documenter:jar:2.0.9:compile, org.apache.maven.reporting:maven-reporting-api=org.apache.maven.reporting:maven-reporting-api:jar:2.0.9:compile, org.apache.maven:maven-repository-metadata=org.apache.maven:maven-repository-metadata:jar:2.0.9:compile, org.apache.maven:maven-error-diagnostics=org.apache.maven:maven-error-diagnostics:jar:2.0.9:compile, org.apache.maven:maven-plugin-descriptor=org.apache.maven:maven-plugin-descriptor:jar:2.0.9:compile, org.apache.maven:maven-monitor=org.apache.maven:maven-monitor:jar:2.0.9:compile, classworlds:classworlds=classworlds:classworlds:jar:1.1:compile, org.apache.maven:maven-toolchain=org.apache.maven:maven-toolchain:jar:2.0.9:compile, org.apache.maven.plugin-tools:maven-plugin-annotations=org.apache.maven.plugin-tools:maven-plugin-annotations:jar:3.1:compile}
[DEBUG]   (f) pluginDescriptor = Component Descriptor: role: 'org.apache.maven.plugin.Mojo', implementation: 'org.apache.maven.plugin.surefire.HelpMojo', role hint: 'org.apache.maven.plugins:maven-surefire-plugin:2.12.4:help'
role: 'org.apache.maven.plugin.Mojo', implementation: 'org.apache.maven.plugin.surefire.SurefirePlugin', role hint: 'org.apache.maven.plugins:maven-surefire-plugin:2.12.4:test'
---
[DEBUG]   (s) printSummary = true
[DEBUG]   (s) projectArtifactMap = {}
[DEBUG]   (s) redirectTestOutputToFile = false
[DEBUG]   (s) remoteRepositories = [      id: central
      url: https://repo.maven.apache.org/maven2
   layout: default
snapshots: [enabled => false, update => daily]
 releases: [enabled => true, update => never]
]
[DEBUG]   (s) reportFormat = brief
[DEBUG]   (s) reportsDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/surefire-reports
[DEBUG]   (s) runOrder = filesystem
[DEBUG]   (s) skip = false
[DEBUG]   (s) skipTests = false
[DEBUG]   (s) testClassesDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/test-classes
[DEBUG]   (s) testFailureIgnore = false
[DEBUG]   (s) testNGArtifactName = org.testng:testng
[DEBUG]   (s) testSourceDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/src/test/java
[DEBUG]   (s) trimStackTrace = true
[DEBUG]   (s) useFile = true
[DEBUG]   (s) useManifestOnlyJar = true
[DEBUG]   (s) useSystemClassLoader = true
[DEBUG]   (s) useUnlimitedThreads = false
[DEBUG]   (s) workingDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002
[DEBUG]   (s) project = MavenProject: com.io7m.bugs:maven-dependency-plugin-20171002:0.0.1 @ /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/pom.xml
[DEBUG]   (s) session = org.apache.maven.execution.MavenSession@cfbc8e8
[DEBUG] -- end configuration --
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ maven-dependency-plugin-20171002 ---
[DEBUG] Dependency collection stats: {ConflictMarker.analyzeTime=0, ConflictMarker.markTime=0, ConflictMarker.nodeCount=74, ConflictIdSorter.graphTime=0, ConflictIdSorter.topsortTime=1, ConflictIdSorter.conflictIdCount=28, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=2, ConflictResolver.conflictItemCount=70, DefaultDependencyCollector.collectTime=33, DefaultDependencyCollector.transformTime=3}
[DEBUG] org.apache.maven.plugins:maven-jar-plugin:jar:2.4:
[DEBUG]    org.apache.maven:maven-plugin-api:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-project:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-settings:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-profile:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-artifact-manager:jar:2.0.6:compile
[DEBUG]          org.apache.maven:maven-repository-metadata:jar:2.0.6:compile
[DEBUG]       org.apache.maven:maven-plugin-registry:jar:2.0.6:compile
[DEBUG]       org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-9-stable-1:compile
[DEBUG]          junit:junit:jar:3.8.1:compile
[DEBUG]          classworlds:classworlds:jar:1.1-alpha-2:compile
[DEBUG]    org.apache.maven:maven-model:jar:2.0.6:runtime
[DEBUG]    org.apache.maven:maven-artifact:jar:2.0.6:compile
[DEBUG]    org.apache.maven:maven-archiver:jar:2.5:compile
[DEBUG]       org.apache.maven:maven-core:jar:2.0.6:compile
[DEBUG]          org.apache.maven:maven-plugin-parameter-documenter:jar:2.0.6:compile
[DEBUG]          org.apache.maven.reporting:maven-reporting-api:jar:2.0.6:compile
[DEBUG]             org.apache.maven.doxia:doxia-sink-api:jar:1.0-alpha-7:compile
[DEBUG]          org.apache.maven:maven-error-diagnostics:jar:2.0.6:compile
[DEBUG]          commons-cli:commons-cli:jar:1.0:compile
[DEBUG]          org.apache.maven:maven-plugin-descriptor:jar:2.0.6:compile
[DEBUG]          org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4:compile
[DEBUG]          org.apache.maven:maven-monitor:jar:2.0.6:compile
[DEBUG]       org.codehaus.plexus:plexus-interpolation:jar:1.15:compile
[DEBUG]    org.codehaus.plexus:plexus-archiver:jar:2.1:compile
[DEBUG]       org.codehaus.plexus:plexus-io:jar:2.0.2:compile
[DEBUG]    commons-lang:commons-lang:jar:2.1:compile
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:3.0:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-jar-plugin:2.4
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-jar-plugin:2.4
[DEBUG]   Imported:  < maven.api
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-jar-plugin:2.4
[DEBUG]   Included: org.apache.maven.plugins:maven-jar-plugin:jar:2.4
[DEBUG]   Included: junit:junit:jar:3.8.1
[DEBUG]   Included: org.apache.maven:maven-archiver:jar:2.5
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-api:jar:2.0.6
[DEBUG]   Included: org.apache.maven.doxia:doxia-sink-api:jar:1.0-alpha-7
[DEBUG]   Included: commons-cli:commons-cli:jar:1.0
[DEBUG]   Included: org.codehaus.plexus:plexus-interactivity-api:jar:1.0-alpha-4
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.15
[DEBUG]   Included: org.codehaus.plexus:plexus-archiver:jar:2.1
[DEBUG]   Included: org.codehaus.plexus:plexus-io:jar:2.0.2
[DEBUG]   Included: commons-lang:commons-lang:jar:2.1
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:3.0
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-jar-plugin:2.4:jar from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-jar-plugin:2.4, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@1b9e1916]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-jar-plugin:2.4:jar' with basic configurator -->
[DEBUG]   (f) classesDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes
[DEBUG]   (f) defaultManifestFile = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/classes/META-INF/MANIFEST.MF
[DEBUG]   (f) finalName = maven-dependency-plugin-20171002-0.0.1
[DEBUG]   (f) forceCreation = false
[DEBUG]   (f) outputDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target
[DEBUG]   (f) project = MavenProject: com.io7m.bugs:maven-dependency-plugin-20171002:0.0.1 @ /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/pom.xml
[DEBUG]   (f) session = org.apache.maven.execution.MavenSession@cfbc8e8
[DEBUG]   (f) skipIfEmpty = false
[DEBUG]   (f) useDefaultManifestFile = false
[DEBUG] -- end configuration --
[DEBUG] isUp2date: false (Destination /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-dependency-plugin-20171002-0.0.1.jar not found.)
[INFO] Building jar: /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target/maven-dependency-plugin-20171002-0.0.1.jar
[DEBUG] adding directory META-INF/
[DEBUG] adding entry META-INF/MANIFEST.MF
[DEBUG] adding directory com/
[DEBUG] adding directory com/io7m/
[DEBUG] adding directory com/io7m/example/
[DEBUG] adding entry module-info.class
[DEBUG] adding entry com/io7m/example/Main.class
[DEBUG] adding directory META-INF/maven/
[DEBUG] adding directory META-INF/maven/com.io7m.bugs/
[DEBUG] adding directory META-INF/maven/com.io7m.bugs/maven-dependency-plugin-20171002/
[DEBUG] adding entry META-INF/maven/com.io7m.bugs/maven-dependency-plugin-20171002/pom.xml
[DEBUG] adding entry META-INF/maven/com.io7m.bugs/maven-dependency-plugin-20171002/pom.properties
[INFO] 
[INFO] --- maven-dependency-plugin:3.0.2:analyze-only (analyze) @ maven-dependency-plugin-20171002 ---
[DEBUG] Dependency collection stats: {ConflictMarker.analyzeTime=1, ConflictMarker.markTime=0, ConflictMarker.nodeCount=291, ConflictIdSorter.graphTime=1, ConflictIdSorter.topsortTime=0, ConflictIdSorter.conflictIdCount=80, ConflictIdSorter.conflictIdCycleCount=0, ConflictResolver.totalTime=6, ConflictResolver.conflictItemCount=198, DefaultDependencyCollector.collectTime=359, DefaultDependencyCollector.transformTime=8}
[DEBUG] org.apache.maven.plugins:maven-dependency-plugin:jar:3.0.2:
[DEBUG]    org.ow2.asm:asm:jar:6.0:runtime
[DEBUG]    org.apache.maven:maven-artifact:jar:3.0:compile
[DEBUG]    org.apache.maven:maven-plugin-api:jar:3.0:compile
[DEBUG]       org.sonatype.sisu:sisu-inject-plexus:jar:1.4.2:compile
[DEBUG]          org.sonatype.sisu:sisu-inject-bean:jar:1.4.2:compile
[DEBUG]             org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7:compile
[DEBUG]    org.apache.maven:maven-model:jar:3.0:compile
[DEBUG]    org.apache.maven:maven-core:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-settings-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-model-builder:jar:3.0:compile
[DEBUG]       org.apache.maven:maven-aether-provider:jar:3.0:runtime
[DEBUG]       org.sonatype.aether:aether-impl:jar:1.7:compile
[DEBUG]          org.sonatype.aether:aether-spi:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-api:jar:1.7:compile
[DEBUG]       org.sonatype.aether:aether-util:jar:1.7:compile
[DEBUG]       org.codehaus.plexus:plexus-interpolation:jar:1.14:compile
[DEBUG]       org.codehaus.plexus:plexus-classworlds:jar:2.2.3:compile
[DEBUG]       org.codehaus.plexus:plexus-component-annotations:jar:1.6:compile
[DEBUG]       org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3:compile
[DEBUG]          org.sonatype.plexus:plexus-cipher:jar:1.4:compile
[DEBUG]    org.apache.maven:maven-repository-metadata:jar:3.0:compile
[DEBUG]    org.apache.maven.reporting:maven-reporting-api:jar:3.0:compile
[DEBUG]    org.apache.maven.reporting:maven-reporting-impl:jar:2.3:compile
[DEBUG]       org.apache.maven.doxia:doxia-core:jar:1.2:compile
[DEBUG]          xerces:xercesImpl:jar:2.9.1:compile
[DEBUG]             xml-apis:xml-apis:jar:1.3.04:compile
[DEBUG]          org.apache.httpcomponents:httpclient:jar:4.0.2:compile
[DEBUG]             org.apache.httpcomponents:httpcore:jar:4.0.1:compile
[DEBUG]       commons-validator:commons-validator:jar:1.3.1:compile
[DEBUG]          commons-beanutils:commons-beanutils:jar:1.7.0:compile
[DEBUG]          commons-digester:commons-digester:jar:1.6:compile
[DEBUG]          commons-logging:commons-logging:jar:1.0.4:compile
[DEBUG]    commons-io:commons-io:jar:2.5:compile
[DEBUG]    org.apache.maven.doxia:doxia-sink-api:jar:1.4:compile
[DEBUG]       org.apache.maven.doxia:doxia-logging-api:jar:1.4:compile
[DEBUG]    org.apache.maven.doxia:doxia-site-renderer:jar:1.4:compile
[DEBUG]       org.apache.maven.doxia:doxia-decoration-model:jar:1.4:compile
[DEBUG]       org.apache.maven.doxia:doxia-module-xhtml:jar:1.4:compile
[DEBUG]       org.apache.maven.doxia:doxia-module-fml:jar:1.4:compile
[DEBUG]       org.codehaus.plexus:plexus-i18n:jar:1.0-beta-7:compile
[DEBUG]       org.codehaus.plexus:plexus-container-default:jar:1.0-alpha-30:compile
[DEBUG]          junit:junit:jar:3.8.1:compile
[DEBUG]       org.codehaus.plexus:plexus-velocity:jar:1.1.7:compile
[DEBUG]       org.apache.velocity:velocity:jar:1.5:compile
[DEBUG]          oro:oro:jar:2.0.8:compile
[DEBUG]       org.apache.velocity:velocity-tools:jar:2.0:compile
[DEBUG]          commons-chain:commons-chain:jar:1.1:compile
[DEBUG]          dom4j:dom4j:jar:1.1:compile
[DEBUG]          sslext:sslext:jar:1.2-0:compile
[DEBUG]          org.apache.struts:struts-core:jar:1.3.8:compile
[DEBUG]             antlr:antlr:jar:2.7.2:compile
[DEBUG]          org.apache.struts:struts-taglib:jar:1.3.8:compile
[DEBUG]          org.apache.struts:struts-tiles:jar:1.3.8:compile
[DEBUG]    org.codehaus.plexus:plexus-archiver:jar:3.4:compile
[DEBUG]       org.apache.commons:commons-compress:jar:1.11:compile
[DEBUG]       org.iq80.snappy:snappy:jar:0.4:compile
[DEBUG]       org.tukaani:xz:jar:1.5:runtime
[DEBUG]    org.codehaus.plexus:plexus-utils:jar:3.0.24:compile
[DEBUG]    org.apache.maven.shared:file-management:jar:1.2.1:compile
[DEBUG]       org.apache.maven.shared:maven-shared-io:jar:1.1:compile
[DEBUG]          org.apache.maven.wagon:wagon-provider-api:jar:1.0-alpha-6:compile
[DEBUG]    org.codehaus.plexus:plexus-io:jar:2.4:compile
[DEBUG]    org.apache.maven.shared:maven-dependency-analyzer:jar:1.7:compile
[DEBUG]    org.apache.maven.shared:maven-dependency-tree:jar:3.0.1:compile
[DEBUG]       org.eclipse.aether:aether-util:jar:0.9.0.M2:compile
[DEBUG]    org.apache.maven.shared:maven-common-artifact-filters:jar:3.0.1:compile
[DEBUG]    org.apache.maven.shared:maven-artifact-transfer:jar:0.9.1:compile
[DEBUG]       commons-codec:commons-codec:jar:1.6:compile
[DEBUG]       org.slf4j:slf4j-api:jar:1.7.5:compile
[DEBUG]    org.apache.maven.shared:maven-shared-utils:jar:3.2.0:compile
[DEBUG]    commons-lang:commons-lang:jar:2.6:compile
[DEBUG]    commons-collections:commons-collections:jar:3.2.2:compile
[DEBUG]    classworlds:classworlds:jar:1.1:compile
[DEBUG] Created new class realm plugin>org.apache.maven.plugins:maven-dependency-plugin:3.0.2
[DEBUG] Importing foreign packages into class realm plugin>org.apache.maven.plugins:maven-dependency-plugin:3.0.2
[DEBUG]   Imported:  < maven.api
[DEBUG] Populating class realm plugin>org.apache.maven.plugins:maven-dependency-plugin:3.0.2
[DEBUG]   Included: org.apache.maven.plugins:maven-dependency-plugin:jar:3.0.2
[DEBUG]   Included: org.ow2.asm:asm:jar:6.0
[DEBUG]   Included: org.sonatype.sisu:sisu-inject-bean:jar:1.4.2
[DEBUG]   Included: org.sonatype.sisu:sisu-guice:jar:noaop:2.1.7
[DEBUG]   Included: org.apache.maven:maven-aether-provider:jar:3.0
[DEBUG]   Included: org.sonatype.aether:aether-util:jar:1.7
[DEBUG]   Included: org.codehaus.plexus:plexus-interpolation:jar:1.14
[DEBUG]   Included: org.codehaus.plexus:plexus-component-annotations:jar:1.6
[DEBUG]   Included: org.sonatype.plexus:plexus-sec-dispatcher:jar:1.3
[DEBUG]   Included: org.sonatype.plexus:plexus-cipher:jar:1.4
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-api:jar:3.0
[DEBUG]   Included: org.apache.maven.reporting:maven-reporting-impl:jar:2.3
[DEBUG]   Included: org.apache.maven.doxia:doxia-core:jar:1.2
[DEBUG]   Included: xerces:xercesImpl:jar:2.9.1
[DEBUG]   Included: xml-apis:xml-apis:jar:1.3.04
[DEBUG]   Included: org.apache.httpcomponents:httpclient:jar:4.0.2
[DEBUG]   Included: org.apache.httpcomponents:httpcore:jar:4.0.1
[DEBUG]   Included: commons-validator:commons-validator:jar:1.3.1
[DEBUG]   Included: commons-beanutils:commons-beanutils:jar:1.7.0
[DEBUG]   Included: commons-digester:commons-digester:jar:1.6
[DEBUG]   Included: commons-logging:commons-logging:jar:1.0.4
[DEBUG]   Included: commons-io:commons-io:jar:2.5
[DEBUG]   Included: org.apache.maven.doxia:doxia-sink-api:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-logging-api:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-site-renderer:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-decoration-model:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-module-xhtml:jar:1.4
[DEBUG]   Included: org.apache.maven.doxia:doxia-module-fml:jar:1.4
[DEBUG]   Included: org.codehaus.plexus:plexus-i18n:jar:1.0-beta-7
[DEBUG]   Included: junit:junit:jar:3.8.1
[DEBUG]   Included: org.codehaus.plexus:plexus-velocity:jar:1.1.7
[DEBUG]   Included: org.apache.velocity:velocity:jar:1.5
[DEBUG]   Included: oro:oro:jar:2.0.8
[DEBUG]   Included: org.apache.velocity:velocity-tools:jar:2.0
[DEBUG]   Included: commons-chain:commons-chain:jar:1.1
[DEBUG]   Included: dom4j:dom4j:jar:1.1
[DEBUG]   Included: sslext:sslext:jar:1.2-0
[DEBUG]   Included: org.apache.struts:struts-core:jar:1.3.8
[DEBUG]   Included: antlr:antlr:jar:2.7.2
[DEBUG]   Included: org.apache.struts:struts-taglib:jar:1.3.8
[DEBUG]   Included: org.apache.struts:struts-tiles:jar:1.3.8
[DEBUG]   Included: org.codehaus.plexus:plexus-archiver:jar:3.4
[DEBUG]   Included: org.apache.commons:commons-compress:jar:1.11
[DEBUG]   Included: org.iq80.snappy:snappy:jar:0.4
[DEBUG]   Included: org.tukaani:xz:jar:1.5
[DEBUG]   Included: org.codehaus.plexus:plexus-utils:jar:3.0.24
[DEBUG]   Included: org.apache.maven.shared:file-management:jar:1.2.1
[DEBUG]   Included: org.apache.maven.shared:maven-shared-io:jar:1.1
[DEBUG]   Included: org.codehaus.plexus:plexus-io:jar:2.4
[DEBUG]   Included: org.apache.maven.shared:maven-dependency-analyzer:jar:1.7
[DEBUG]   Included: org.apache.maven.shared:maven-dependency-tree:jar:3.0.1
[DEBUG]   Included: org.eclipse.aether:aether-util:jar:0.9.0.M2
[DEBUG]   Included: org.apache.maven.shared:maven-common-artifact-filters:jar:3.0.1
[DEBUG]   Included: org.apache.maven.shared:maven-artifact-transfer:jar:0.9.1
[DEBUG]   Included: commons-codec:commons-codec:jar:1.6
[DEBUG]   Included: org.apache.maven.shared:maven-shared-utils:jar:3.2.0
[DEBUG]   Included: commons-lang:commons-lang:jar:2.6
[DEBUG]   Included: commons-collections:commons-collections:jar:3.2.2
[DEBUG] Configuring mojo org.apache.maven.plugins:maven-dependency-plugin:3.0.2:analyze-only from plugin realm ClassRealm[plugin>org.apache.maven.plugins:maven-dependency-plugin:3.0.2, parent: jdk.internal.loader.ClassLoaders$AppClassLoader@1b9e1916]
[DEBUG] Configuring mojo 'org.apache.maven.plugins:maven-dependency-plugin:3.0.2:analyze-only' with basic configurator -->
[DEBUG]   (f) analyzer = default
[DEBUG]   (f) baseDir = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002
[DEBUG]   (f) failOnWarning = true
[DEBUG]   (f) ignoreNonCompile = false
[DEBUG]   (f) outputDirectory = /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/target
[DEBUG]   (f) outputXML = false
[DEBUG]   (f) project = MavenProject: com.io7m.bugs:maven-dependency-plugin-20171002:0.0.1 @ /home/someone/git/com.github/io7m/maven-dependency-plugin-20171002/pom.xml
[DEBUG]   (f) scriptableFlag = $$%%%
[DEBUG]   (f) scriptableOutput = false
[DEBUG]   (f) skip = false
[DEBUG]   (f) verbose = false
[DEBUG] -- end configuration --
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 3.625 s
[INFO] Finished at: 2017-10-02T15:36:47Z
[INFO] Final Memory: 18M/61M
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-dependency-plugin:3.0.2:analyze-only (analyze) on project maven-dependency-plugin-20171002: Execution analyze of goal org.apache.maven.plugins:maven-dependency-plugin:3.0.2:analyze-only failed: Unknown constant pool type -> [Help 1]
org.apache.maven.lifecycle.LifecycleExecutionException: Failed to execute goal org.apache.maven.plugins:maven-dependency-plugin:3.0.2:analyze-only (analyze) on project maven-dependency-plugin-20171002: Execution analyze of goal org.apache.maven.plugins:maven-dependency-plugin:3.0.2:analyze-only failed: Unknown constant pool type
	at org.apache.maven.lifecycle.internal.MojoExecutor.execute(MojoExecutor.java:213)
	at org.apache.maven.lifecycle.internal.MojoExecutor.execute(MojoExecutor.java:154)
	at org.apache.maven.lifecycle.internal.MojoExecutor.execute(MojoExecutor.java:146)
	at org.apache.maven.lifecycle.internal.LifecycleModuleBuilder.buildProject(LifecycleModuleBuilder.java:117)
	at org.apache.maven.lifecycle.internal.LifecycleModuleBuilder.buildProject(LifecycleModuleBuilder.java:81)
	at org.apache.maven.lifecycle.internal.builder.singlethreaded.SingleThreadedBuilder.build(SingleThreadedBuilder.java:51)
	at org.apache.maven.lifecycle.internal.LifecycleStarter.execute(LifecycleStarter.java:128)
	at org.apache.maven.DefaultMaven.doExecute(DefaultMaven.java:309)
	at org.apache.maven.DefaultMaven.doExecute(DefaultMaven.java:194)
	at org.apache.maven.DefaultMaven.execute(DefaultMaven.java:107)
	at org.apache.maven.cli.MavenCli.execute(MavenCli.java:993)
	at org.apache.maven.cli.MavenCli.doMain(MavenCli.java:345)
	at org.apache.maven.cli.MavenCli.main(MavenCli.java:191)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.base/java.lang.reflect.Method.invoke(Method.java:564)
	at org.codehaus.plexus.classworlds.launcher.Launcher.launchEnhanced(Launcher.java:289)
	at org.codehaus.plexus.classworlds.launcher.Launcher.launch(Launcher.java:229)
	at org.codehaus.plexus.classworlds.launcher.Launcher.mainWithExitCode(Launcher.java:415)
	at org.codehaus.plexus.classworlds.launcher.Launcher.main(Launcher.java:356)
Caused by: org.apache.maven.plugin.PluginExecutionException: Execution analyze of goal org.apache.maven.plugins:maven-dependency-plugin:3.0.2:analyze-only failed: Unknown constant pool type
	at org.apache.maven.plugin.DefaultBuildPluginManager.executeMojo(DefaultBuildPluginManager.java:145)
	at org.apache.maven.lifecycle.internal.MojoExecutor.execute(MojoExecutor.java:208)
	... 20 more
Caused by: java.lang.RuntimeException: Unknown constant pool type
	at org.apache.maven.shared.dependency.analyzer.asm.ConstantPoolParser.parseConstantPoolClassReferences(ConstantPoolParser.java:96)
	at org.apache.maven.shared.dependency.analyzer.asm.ConstantPoolParser.getConstantPoolClassReferences(ConstantPoolParser.java:77)
	at org.apache.maven.shared.dependency.analyzer.asm.DependencyClassFileVisitor.visitClass(DependencyClassFileVisitor.java:67)
	at org.apache.maven.shared.dependency.analyzer.ClassFileVisitorUtils.visitClass(ClassFileVisitorUtils.java:163)
	at org.apache.maven.shared.dependency.analyzer.ClassFileVisitorUtils.acceptDirectory(ClassFileVisitorUtils.java:143)
	at org.apache.maven.shared.dependency.analyzer.ClassFileVisitorUtils.accept(ClassFileVisitorUtils.java:71)
	at org.apache.maven.shared.dependency.analyzer.asm.ASMDependencyAnalyzer.analyze(ASMDependencyAnalyzer.java:50)
	at org.apache.maven.shared.dependency.analyzer.DefaultProjectDependencyAnalyzer.buildDependencyClasses(DefaultProjectDependencyAnalyzer.java:211)
	at org.apache.maven.shared.dependency.analyzer.DefaultProjectDependencyAnalyzer.buildDependencyClasses(DefaultProjectDependencyAnalyzer.java:198)
	at org.apache.maven.shared.dependency.analyzer.DefaultProjectDependencyAnalyzer.analyze(DefaultProjectDependencyAnalyzer.java:74)
	at org.apache.maven.plugins.dependency.analyze.AbstractAnalyzeMojo.checkDependencies(AbstractAnalyzeMojo.java:298)
	at org.apache.maven.plugins.dependency.analyze.AbstractAnalyzeMojo.execute(AbstractAnalyzeMojo.java:250)
	at org.apache.maven.plugin.DefaultBuildPluginManager.executeMojo(DefaultBuildPluginManager.java:134)
	... 21 more
[ERROR] 
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/PluginExecutionException
