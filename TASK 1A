//Task 1A: Transpose of a Rectangular Matrix (Using Two Matrices)
#include <iostream>
using namespace std;
int main() {
    cout << "Enter the row and col : ";
    int r,c;
    cin >> r >> c;

    int A[r][c] , T[c][r];
    cout << "Enter the Elements : " << endl;
    for(int i=0; i<r; i++) {
        for(int j=0; j<c; j++) {
            cin >> A[i][j];
        }
    }

    for(int i=0; i<r; i++) {
        for(int j=0; j<c; j++) {
            T[j][i] = A[i][j];
        }
    }
    for(int i=0; i<c; i++) {
        for(int j=0; j<r; j++) {
            cout << T[i][j] << " ";
        }
        cout << endl;
    }
}

/*
//For Modify the existing matrix without using a second matrix. 
#include <iostream>
using namespace std;
int main() {
    cout << "Enter the row and col : ";
    int r,c;
    cin >> r >> c;

    int A[r][c] , T[c][r];
    cout << "Enter the Elements : " << endl;
    for(int i=0; i<r; i++) {
        for(int j=0; j<c; j++) {
            cin >> A[i][j];
        }
    }

    for(int i=0; i<r; i++) {
        for(int j=i+1; j<c; j++) {
            swap(A[i][j], A[j][i]);
        }
    }
    for(int i=0; i<c; i++) {
        for(int j=0; j<r; j++) {
            cout << A[i][j] << " ";
        }
        cout << endl;
    }
}
*/
