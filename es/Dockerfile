FROM elasticsearch:5.1

# x-pack をインストール
RUN elasticsearch-plugin install --batch x-pack

# kuromojiをインストール
RUN elasticsearch-plugin install analysis-kuromoji

# icu-normalizerをインストール
RUN elasticsearch-plugin install analysis-icu

# Elasticsearch Analysis Kuromoji Neologd をインストール
RUN elasticsearch-plugin install org.codelibs:elasticsearch-analysis-kuromoji-neologd:5.1.0
