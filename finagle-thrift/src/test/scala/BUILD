junit_tests(name='scala',
  dependencies=[
    pants('3rdparty:junit'),
    pants('3rdparty:mockito-all'),
    pants('3rdparty:netty'),
    pants('3rdparty:scalatest'),
    pants('3rdparty:specs'),
    pants('3rdparty:thrift-0.5.0'),
    pants('finagle/finagle-core'),
    pants('finagle/finagle-test'),
    pants('finagle/finagle-thrift'),
    pants('finagle/finagle-thrift/src/test/java'),
    pants('util/util-core'),

    pants(':silly-thrift-dep'),
  ],
  sources=rglobs('*.scala')
)

jar_library(name='silly-thrift-dep',
  dependencies=[
    jar(org='silly', name='silly-thrift', rev='0.5.0'),
  ],
)
