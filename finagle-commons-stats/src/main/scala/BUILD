scala_library(name='scala',
  dependencies=[
    pants('3rdparty/jvm/com/twitter/common:stats'),
    pants('finagle/finagle-core')
  ],
  sources=rglobs('*.scala'),
  resources=[
    pants('finagle/finagle-commons-stats/src/main/resources')
  ],
  provides=artifact(org='com.twitter',
                    name='finagle-commons-stats',
                    repo='pants-support/ivy:internal',),
)
