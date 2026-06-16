
all : 01_市民自治の知識と実践.pdf 02_日本政治思想史.pdf 03_中世西洋史.pdf 04_現実と向き合う政治理論.pdf

01_市民自治の知識と実践.pdf : 01_市民自治の知識と実践.tex
	ptex2pdf -l 01_市民自治の知識と実践

02_日本政治思想史.pdf : 02_日本政治思想史.tex
	ptex2pdf -l 02_日本政治思想史.tex

03_中世西洋史.pdf : 03_中世西洋史.tex
	ptex2pdf -l 03_中世西洋史.tex

04_現実と向き合う政治理論.pdf : 04_現実と向き合う政治理論.tex
	ptex2pdf -l 04_現実と向き合う政治理論.tex

clean :
	\rm -f *.aux
	\rm -f *.log
	\rm -f *.pdf
