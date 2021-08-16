# brl-converter-frontend

### environment requirements
- npm 6.14.6+
- node 12.18.3+
- `npm install`

### local test
- run(local): `npx http-server`

### feature
- visualize uploaded brl format file to braille text(1)
- convert img to braille text(2) by network call 
- visualize braille text(2) 
- compare uploaded braille text(1) and converted braille text(2)
- comparison algorithm is `"An O(ND) Difference Algorithm and its Variations" (Myers, 1986)`

### using package
- jsdiff (https://github.com/kpdecker/jsdiff)
- angerinaReader (https://github.com/IlyaOvodov/AngelinaReader)
