FROM docker.elastic.co/elasticsearch/elasticsearch:7.9.2
LABEL maintainer Tomoyuki Sugiyama <tomoyuki.sugiyama.j7u@jpgr.denso.com>


# kuromojiをインストール
RUN elasticsearch-plugin install analysis-kuromoji
#RUN ES_JAVA_OPTS="-DproxyHost=set.your.proxy.ip -DproxyPort=8080 -Dhttps.proxyHost=set.your.proxy.ip -Dhttps.proxyPort=8080" elasticsearch-plugin install analysis-kuromoji
