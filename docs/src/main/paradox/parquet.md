# Parquet Connector

The Parquet connector provides Sinks for producing files in the [Parquet format](https://parquet.apache.org/), which
is commonly used by data processing frameworks.

### Reported issues

[Tagged issues at Github](https://github.com/akka/alpakka/labels/p%3Aparquet)

## Artifacts

@@dependency [sbt,Maven,Gradle] {
  group=com.lightbend.akka
  artifact=akka-stream-alpakka-parquet_$scalaBinaryVersion$
  version=$version$
}

## Usage

First, create a @scaladoc[ParquetSettings](akka.stream.alpakka.parquet.ParquetSettings$) instance.

Scala
: @@snip ($alpakka$/parquet/src/test/scala/akka/stream/alpakka/parquet/scaladsl/ParquetSinkSpec.scala) { #basic-settings }
