# [liveSense :: Framework :: Apache Solr Indexer/Search engine - org.liveSense.framework.solr](http://github.com/liveSense/org.liveSense.framework.solr)

## Description
A Solr bundle that embeds Solr 4 into OSGi

## OSGi Exported packages
* org.apache.solr(4.0.0)
* org.apache.solr.analysis(4.0.0)
* org.apache.solr.client.solrj(4.0.0)
* org.apache.solr.client.solrj.beans(4.0.0)
* org.apache.solr.client.solrj.embedded(4.0.0)
* org.apache.solr.client.solrj.impl(4.0.0)
* org.apache.solr.client.solrj.request(4.0.0)
* org.apache.solr.client.solrj.response(4.0.0)
* org.apache.solr.client.solrj.util(4.0.0)
* org.apache.solr.cloud(4.0.0)
* org.apache.solr.common(4.0.0)
* org.apache.solr.common.cloud(4.0.0)
* org.apache.solr.common.luke(4.0.0)
* org.apache.solr.common.params(4.0.0)
* org.apache.solr.common.util(4.0.0)
* org.apache.solr.core(4.0.0)
* org.apache.solr.handler(4.0.0)
* org.apache.solr.handler.admin(4.0.0)
* org.apache.solr.handler.component(4.0.0)
* org.apache.solr.handler.loader(4.0.0)
* org.apache.solr.highlight(4.0.0)
* org.apache.solr.internal.csv(4.0.0)
* org.apache.solr.internal.csv.writer(4.0.0)
* org.apache.solr.logging(4.0.0)
* org.apache.solr.logging.jul(4.0.0)
* org.apache.solr.request(4.0.0)
* org.apache.solr.response(4.0.0)
* org.apache.solr.response.transform(4.0.0)
* org.apache.solr.schema(4.0.0)
* org.apache.solr.search(4.0.0)
* org.apache.solr.search.function(4.0.0)
* org.apache.solr.search.function.distance(4.0.0)
* org.apache.solr.search.grouping(4.0.0)
* org.apache.solr.search.grouping.collector(4.0.0)
* org.apache.solr.search.grouping.distributed(4.0.0)
* org.apache.solr.search.grouping.distributed.command(4.0.0)
* org.apache.solr.search.grouping.distributed.requestfactory(4.0.0)
* org.apache.solr.search.grouping.distributed.responseprocessor(4.0.0)
* org.apache.solr.search.grouping.distributed.shardresultserializer(4.0.0)
* org.apache.solr.search.grouping.endresulttransformer(4.0.0)
* org.apache.solr.search.similarities(4.0.0)
* org.apache.solr.servlet(4.0.0)
* org.apache.solr.servlet.cache(4.0.0)
* org.apache.solr.spelling(4.0.0)
* org.apache.solr.spelling.suggest(4.0.0)
* org.apache.solr.spelling.suggest.fst(4.0.0)
* org.apache.solr.spelling.suggest.jaspell(4.0.0)
* org.apache.solr.spelling.suggest.tst(4.0.0)
* org.apache.solr.update(4.0.0)
* org.apache.solr.update.processor(4.0.0)
* org.apache.solr.util(4.0.0)
* org.apache.solr.util.plugin(4.0.0)
* org.apache.solr.util.xslt(4.0.0)

## OSGi Dependencies
* __System Bundle - org.apache.felix.framework (4.0.3)__
	* javax.management
	* javax.management.openmbean
	* javax.management.remote
	* javax.naming
	* javax.script
	* javax.xml.namespace
	* javax.xml.namespace
	* javax.xml.parsers
	* javax.xml.parsers
	* javax.xml.stream
	* javax.xml.stream
	* javax.xml.transform
	* javax.xml.transform
	* javax.xml.transform.dom
	* javax.xml.transform.dom
	* javax.xml.transform.sax
	* javax.xml.transform.sax
	* javax.xml.transform.stream
	* javax.xml.transform.stream
	* javax.xml.xpath
	* javax.xml.xpath
	* org.w3c.dom
	* org.w3c.dom
	* org.xml.sax
	* org.xml.sax
	* org.xml.sax.ext
	* org.xml.sax.ext
* __Apache Lucene :: Queries - lucene-queries (4.0.0.1-SNAPSHOT)__
	* org.apache.lucene.queries.function
	* org.apache.lucene.queries.function.docvalues
	* org.apache.lucene.queries.function.valuesource
	* org.apache.lucene.queries.mlt
* __Woodstox XML-processor - woodstox-core-asl (4.2.0)__
	* com.ctc.wstx.stax
* __Apache Lucene :: Suggest - lucene-suggest (4.0.0.1-SNAPSHOT)__
	* org.apache.lucene.search.spell
	* org.apache.lucene.search.suggest
	* org.apache.lucene.search.suggest.fst
	* org.apache.lucene.search.suggest.jaspell
	* org.apache.lucene.search.suggest.tst
* __Apache HttpCore OSGi bundle - org.apache.httpcomponents.httpcore (4.1.2)__
	* org.apache.http
	* org.apache.http.entity
	* org.apache.http.message
	* org.apache.http.params
	* org.apache.http.protocol
	* org.apache.http.util
* __Apache HttpClient OSGi bundle - org.apache.httpcomponents.httpclient (4.1.2)__
	* org.apache.http.auth
	* org.apache.http.client
	* org.apache.http.client.entity
	* org.apache.http.client.methods
	* org.apache.http.client.params
	* org.apache.http.conn
	* org.apache.http.entity.mime
	* org.apache.http.entity.mime.content
	* org.apache.http.impl.client
	* org.apache.http.impl.conn.tsccm
* __Apache Lucene :: Query Parsers - lucene-queryparser (4.0.0.1-SNAPSHOT)__
	* org.apache.lucene.queryparser.classic
	* org.apache.lucene.queryparser.surround.parser
	* org.apache.lucene.queryparser.surround.query
* __Apache Commons IO Bundle - org.apache.commons.io (1.4)__
	* org.apache.commons.io
* __Commons FileUpload - org.apache.commons.fileupload (1.2.2)__
	* org.apache.commons.fileupload
	* org.apache.commons.fileupload.disk
	* org.apache.commons.fileupload.servlet
* __Servlet 3.0 - org.apache.geronimo.specs.geronimo-servlet_3.0_spec (1.0)__
	* javax.servlet
	* javax.servlet
	* javax.servlet.http
	* javax.servlet.http
* __Commons Lang - org.apache.commons.lang (2.6)__
	* org.apache.commons.lang
* __Apache Lucene :: Spatial Strategies - lucene-spatial (4.0.0.1-SNAPSHOT)__
	* com.spatial4j.core.context
	* com.spatial4j.core.distance
	* com.spatial4j.core.exception
	* com.spatial4j.core.io
	* com.spatial4j.core.shape
	* org.apache.lucene.spatial
	* org.apache.lucene.spatial.prefix
	* org.apache.lucene.spatial.prefix.tree
	* org.apache.lucene.spatial.query
	* org.apache.lucene.spatial.vector
* __Jetty :: Aggregate :: All Server - org.eclipse.jetty.aggregate.jetty-all-server (8.1.9.v20130131)__
	* org.eclipse.jetty.server
	* org.eclipse.jetty.server.bio
	* org.eclipse.jetty.server.handler
	* org.eclipse.jetty.server.session
	* org.eclipse.jetty.servlet
	* org.eclipse.jetty.util.component
	* org.eclipse.jetty.util.log
	* org.eclipse.jetty.util.thread
* __Commons Codec - org.apache.commons.codec (1.6.0)__
	* org.apache.commons.codec.binary
* __Apache Lucene :: Analyzers :: Common - lucene-analyzers-common (4.0.0.1-SNAPSHOT)__
	* org.apache.lucene.analysis.charfilter
	* org.apache.lucene.analysis.core
	* org.apache.lucene.analysis.util
	* org.apache.lucene.collation
* __OPS4J Pax Logging - API - org.ops4j.pax.logging.pax-logging-api (1.7.0)__
	* org.slf4j
	* org.slf4j
	* org.slf4j
	* org.slf4j
* __Apache ServiceMix :: Bundles :: guava - org.apache.servicemix.bundles.guava (11.0.0.1)__
	* com.google.common.base
	* com.google.common.collect
* __Apache Lucene :: Core - lucene-core (4.0.0.1-SNAPSHOT)__
	* org.apache.lucene
	* org.apache.lucene.analysis
	* org.apache.lucene.analysis.tokenattributes
	* org.apache.lucene.codecs
	* org.apache.lucene.codecs.lucene40
	* org.apache.lucene.document
	* org.apache.lucene.document
	* org.apache.lucene.index
	* org.apache.lucene.index
	* org.apache.lucene.search
	* org.apache.lucene.search.similarities
	* org.apache.lucene.store
	* org.apache.lucene.store
	* org.apache.lucene.util
	* org.apache.lucene.util.automaton
	* org.apache.lucene.util.mutable
	* org.apache.lucene.util.packed
* __Apache Lucene :: Grouping - lucene-grouping (4.0.0.1-SNAPSHOT)__
	* org.apache.lucene.search.grouping
	* org.apache.lucene.search.grouping.function
	* org.apache.lucene.search.grouping.term
* __Apache Lucene :: Highlighter - lucene-highlighter (4.0.0.1-SNAPSHOT)__
	* org.apache.lucene.search.highlight
	* org.apache.lucene.search.vectorhighlight

## OSGi Embedded JARs
* solr-core-4.0.0.jar
* solr-solrj-4.0.0.jar

## Dependency Graph
![alt text](http://raw.github.com.everydayimmirror.in/liveSense/org.liveSense.framework.solr/master/osgidependencies.svg "")