FROM k8scc01covidacr.azurecr.io/ml-workspace-rstudio:test

USER root

RUN $RESOURCES_PATH/tools/qgis.sh

USER jovyan

CMD ["/init.sh"]