# Fortune Cookies
> Would you like to have some fortune cookies?
> http://103.167.136.89:10088/

## About the Challenge
Diberikan sebuah link Website yang memunculkan isi dari fortune cookie

![images](images/FC_Before.png)

## Solution
Berdasarkan hint challenge dan bentuk dari link webnya bisa disimpulkan bahwa flag terdapat pada cookie yang ada, Maka dari itu, dengan menggunakan inspect 

![images](images/FC_ChangeFlagValue.png)

Pilih bagian application lalu ke storage dan pada bagian cookie ubah value pada flag dari 0 menjadi 1

![images](images/FC_FlagValueChanged.png)

ini akan menampilkan flag 

![images](images/FC_Flag.png)

```shell
ForestyHC{here_is_your_fortun3_cookie_4a0a47}
```
