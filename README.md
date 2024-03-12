# -static-

int product(int);





int main()
{
    printf("%d\n",product(1));
    printf("%d\n",product(2));
    printf("%d\n",product(3));

    return 0;
}

int product(int n){
    
   static   int productN=1;   //靜態宣告
   productN=productN*n;
   return productN;
    
    
}

//結果出來是1,2,6因為我有設靜態宣告,沒有靜態宣告會是1,2,3







