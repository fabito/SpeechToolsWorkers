all: blank studio sejm pkf

blank:
	docker build -t danijel3/clarin-pl-speechtools -f Dockerfile .

studio:
	docker build -t danijel3/clarin-pl-speechtools:studio -f Dockerfile.studio .

sejm:
	docker build -t danijel3/clarin-pl-speechtools:sejm -f Dockerfile.sejm .

pkf:
	docker build -t danijel3/clarin-pl-speechtools:pkf -f Dockerfile.pkf .
