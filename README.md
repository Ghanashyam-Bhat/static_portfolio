## Portfolio

Portfolio was developed using react + go
https://github.com/Ghanashyam-Bhat/portfolio

Later downloaded as html to host using github pages
```
wget --recursive --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains shyam.pinakatech.in --no-parent http://shyam.pinakatech.in
```

Fix the absolute image paths inside the downloaded JavaScript files

linux
```
find portfolio.pinakatech.in -type f -name "*.js" -exec sed -i 's|"/images/|"./images/|g' {} +
```

mac
```
find portfolio.pinakatech.in -type f -name "*.js" -exec sed -i '' 's|"/images/|"./images/|g' {} +
```
