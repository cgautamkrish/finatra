scala_library(name='scala',
  provides = scala_artifact(
    org = 'com.twitter.inject',
    name = 'inject-thrift-client',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/com/google/inject:guice',
    '3rdparty/jvm/joda-time:joda-time',
    '3rdparty/jvm/com/github/nscala_time:nscala_time',
    'finagle/finagle-core',
    'finagle/finagle-thrift',
    'finagle/finagle-thriftmux',
    'finatra/inject/inject-core',
    'scrooge/scrooge-core',
    'util/util-core',
  ],
  sources=rglobs('*.scala'),
)
