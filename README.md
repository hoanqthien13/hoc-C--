#include <iostream>
using namespace std;

//hàm tính diện tích hai số nguyên dài và rộng
int tinh_dien_tich(int dai, int rong) {
    return dai * rong;
}

// In "Xin chào" mà không cần số nguyên
void xin_chao (string ten) {
    cout << "Xin chào" << ten << endl;
}

// Hàm main để chạy chương trình
int main() {
   xin_chao("hthienexe");

   // gọi hàm tính diện tích 
   int ket_qua = tinh_dien_tich(10, 20);
   cout << "Diện tích là:" << ket_qua << endl;

   return 0;
}
