# OBuildFactory built rpms

## OpenJDK8 rpms for CentOS 7

The following command was used to build them:

export JAVA_HOME=/usr/lib/jvm/java-1.7.0
XPACKAGE=true XCLEAN=true XUSE_NEW_BUILD_SYSTEM=true XBUILD=true ./obuildfactory/openjdk8/linux/standalone-job.sh 
