all: init 1a 1b 1c
init:	init_tree.png
1a:	tree1a.png
1b:	tree1b.png
1c:	tree1c.png
%.png:	%.dot
	dot -Tpng $< -o $@
clean:
	rm *.png

