FROM kibana:latest


RUN kibana plugin --install elasticsearch/marvel/latest \
    && chown kibana:kibana /opt/kibana/optimize/.babelcache.json
