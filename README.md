let jumlahAngkot = 10;
let angkotBeroprasi = 6;
let noAngkot = 1;

//menggunakan while()
while (noAngkot <= angkotBeroprasi) { 
    console.log(`angkot NO ${noAngkot} beroprasi dengan baik`);
    
noAngkot++;
}

//menggunakan for()
for( noAngkot = angkotBeroprasi +1; noAngkot <= jumlahAngkot; noAngkot++) {
    console.log(`angkot NO ${noAngkot} sedang tidak beroprasi`);
}
