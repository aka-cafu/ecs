FROM fluent/fluentd:stable
RUN gem install fluent-plugin-elasticsearch --no-rdoc --no-ri && \
    gem install fluent-plugin-beats --no-document && \
    gem install fluent-plugin-forest --no-document && \
    gem install fluent-plugin-record-reformer --no-document && \
    gem install fluent-plugin-concat
COPY fluent.conf /fluentd/etc/
