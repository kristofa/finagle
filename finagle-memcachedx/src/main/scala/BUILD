scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'finagle-memcachedx',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/com/fasterxml/jackson/core:jackson-core',
    '3rdparty/jvm/com/fasterxml/jackson/core:jackson-databind',
    '3rdparty/jvm/com/fasterxml/jackson/module:jackson-module-scala',
    '3rdparty/jvm/com/google/guava',
    '3rdparty/jvm/com/twitter/common/zookeeper:client',
    '3rdparty/jvm/com/twitter/common/zookeeper:server-set',
    '3rdparty/jvm/com/twitter/common:io',
    '3rdparty/jvm/com/twitter/common:quantity',
    '3rdparty:gson',
    '3rdparty:netty',
    '3rdparty:zookeeper',
    'finagle/finagle-core',
    'finagle/finagle-serversets',
    'util/util-core',
    'util/util-hashing',
  ],
  sources=rglobs('*.scala'),
  resources=[
    'finagle/finagle-memcachedx/src/main/resources'
  ],
)
