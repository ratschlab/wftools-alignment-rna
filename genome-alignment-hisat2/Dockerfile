FROM ratschlab/wf-base-miniconda4.8.3:v1.0.1

LABEL org.opencontainers.image.source https://github.com/ratschlab/wftools-alignment-rna

ENV PATH="/tools:${PATH}"

COPY *.py /tools/

ENTRYPOINT ["/usr/bin/env"]

CMD ["/bin/bash"]
