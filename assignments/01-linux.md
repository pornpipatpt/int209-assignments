# Linux assignment

## 1. Excercise File
Create wipcamp12 directory inside your home directory


Create programmer, website, network and ux-ui directory inside wipcamp12 directory


Create slide01.txt file inside your wipcamp12 directory


Copy slide01.txt to slide02.txt and slide03.txt inside wipcamp12 directory


Copy wipcamp12 directory to wipcamp13


Delete slide03.txt inside wipcamp13

Move slide01.txt inside wipcamp12 to newslide.txt inside wipcamp13

Delete wipcamp12 and wipcamp13

```bash
mkdir wipcamp12
mkdir programmer,website,network,ui-ux
touch wipcamp12/slide01.txt
cp wipcamp12/slide01.txt wipcamp12/slide02.txt
cp wipcamp12/slide01.txt wipcamp12/slide03.txt
cp -r wipcamp12 wipcamp13
rm wipcamp13/slide03.txt
mv wipcamp12/slide01.txt wipcamp13/
rm -r wipcamp12
rm -r wipcamp13


