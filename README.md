# First-Unique-Character-in-a-String

#include<iostream>
#include<string>
using namespace std ;
int main(){
string s ;
cout<<" enter a name ";
cin>>s;
 for(int i=0;s[i]!='\0';i++){
 int count =0;
 for(int j=0;j<s.size();j++){
 if (i != j&&s[i]==s[j]){
  count++;
  }
  }
 if (count == 0){
 cout << i << endl;
 break;
  }
    }

return 0;
};
