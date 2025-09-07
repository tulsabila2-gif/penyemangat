#include <iostream>
#include <chrono>
#include <thread>

using namespace std;
using namespace chrono;
using namespace this_thread;

int main()    {

       string text ="Hai, aku tau kamu capek sama semuanya, aku tau kamu kecewa, sedih, tapi coba kamu lihat sekitar kamu, dunia masih tetap berjalan walaupun kamu sedang sedih. Capek itu wajar karena kita cuma manusia bukan robot, yang ga wajar itu kalau kamu mulai berani menyakiti diri kamu sendiri hanya untuk melampiaskan emosi kamu, tolong jangan pernah lakuin itu ya? kamu bisa kok ngelakuin hal lain kayak muter-muter keliling jalanan, beli makanan yang kamu suka, sendiri juga gapapa kok kalau kamu nyaman sendiri. Bahagia itu sederhana, dan alasan bahagia itu ya dari diri kamu sendiri";
    
       for(char c : text) {
           cout<<c;
           cout.flush();
           
           sleep_for(milliseconds(80));
}


return 0;
}
