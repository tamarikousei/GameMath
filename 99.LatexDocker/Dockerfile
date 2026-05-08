FROM paperist/texlive-ja:latest

# 数学教材作成用のパッケージを追加
RUN tlmgr update --self && \
    tlmgr install physics pgf pgfplots tikz-cd