FROM rocker/rstudio
MAINTAINER Christian Panse <cp@fgcz.ethz.ch>

RUN echo "install.packages(c('maptools', 'seqinr', 'ggplot2', 'shiny', 'Rmpfr'))" \ 
  | R --no-save \
  && mkdir /tmp/XLinkX && cd /tmp/XLinkX \
  && wget 'https://sourceforge.net/projects/xlinkx/files/XlinkX_training.zip/download' -O XlinkX_training.zip \
  && wget 'http://sourceforge.net/projects/xlinkx/files/XlinkX_20151227.zip/download' -O XlinkX_20151227.zip
