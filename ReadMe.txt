Setelah menjalankan server dengan npm run start, lakukan command berikut pada terminal/CMD/Gitbash :

curl -X GET http://localhost:5000/
// output: {"message":"Ini adalah homepage"}
curl -X GET http://localhost:5000/about
// output: {"message":"Halo! ini adalah halaman about"}
curl -X DELETE http://localhost:5000/
// output: {"message":"Halaman tidak dapat diakses dengan DELETE request"}