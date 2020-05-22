FROM k8scc01covidacr.azurecr.io/ml-workspace-base:test

RUN sudo $RESOURCES_PATH/tools/r-runtime.sh && \
    sudo $RESOURCES_PATH/tools/r-studio-desktop.sh 

CMD ["/init.sh"]