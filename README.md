let jumlahAngkot = 10;
let angkotBeroprasi = 6;
let noAngkot = 1;

//if else
for( noAngkot = noAngkot; noAngkot <= jumlahAngkot; noAngkot++)

    if( noAngkot <= angkotBeroprasi) {
        console.log(`angkot no ${noAngkot} sedang beroprasi`);
    } else if (noAngkot === 8) {
        console.log(`angkot no ${noAngkot} sedang lembur`);
    } else {
        console.log(`angkot no ${noAngkot} sedang tidak beroprasi`)
    }
        
