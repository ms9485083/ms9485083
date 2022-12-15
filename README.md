#include <iostream>
using namespace std;
int main() {
    float amount,result;
 string coin1,coin2;
 cout<<"Welcome\n"; 
 cout<<"Please, enter the first Coin\n";
 cin>>coin1;
 cout<<"Please, enter the value \n";
 cin>>amount;
 cout<<"Please, enter another Coin\n";
 cin>>coin2;
    //egyptian_pound
    
    if(coin1=="egyptian_pound"&&coin2=="riyal"){
         result=0.15*amount;
    cout<<result<<" riyal";}
    else if(coin1=="egyptian_pound"&&coin2=="dollar"){
         result=0.041*amount;
    cout<<result<<" dollar";}
    else if(coin1=="egyptian_pound"&&coin2=="won"){
         result=0.18*amount;
    cout<<result<<" won";}
    else if(coin1=="egyptian_pound"&&coin2=="franc"){
         result=0.038*amount;
    cout<<result<<" franc";}
    else if(coin1=="egyptian_pound"&&coin2=="euro"){
         result=0.039*amount;
    cout<<result<<" euro";}
    else if(coin1=="egyptian_pound"&&coin2=="sterling_pound"){
         result=0.033*amount;
    cout<<result<<" sterling_pound";}
    else if(coin1=="egyptian_pound"&&coin2=="kuwaiti_pound"){
         result=0.012*amount;
    cout<<result<<" kuwaiti_pound";}
    else if(coin1=="egyptian_pound"&&coin2=="dirham"){
         result=0.15*amount;
    cout<<result<<" dirham";}




   // riyal
   
     else if (coin1 == "riyal" && coin2== "egyptian_pound"){
           result=6.47*amount;
    cout<<result<<" egyptian pound";}
    else if (coin1 == "riyal" && coin2 =="euro" ){
        result=0.27*amount;
      cout <<result << "euro";}
    else if (coin1 == "riyal" && coin2=="dollar"){
      result=0.26*amount;
      cout <<result<<" dollar";}
      else if(coin1 =="riyal " && coin2=="franc"){
      result=0.026*amount;
      cout << result <<" franc " ;}
     else if (coin1 == "riyal" && coin2 =="won"){
      result=366.76*amount;
      cout << result << " won " ;}
     else if (coin1 =="riyal" && coin2 =="sterling_pound" ){
      result=0.23*amount;
      cout << result << " sterling_pound " ;}
    else if (coin1 =="riyal"&& coin2 =="kuwaiti_pound" ){
      result=0.082*amount;
      cout << result << " kuwaiti_pound" ;}
    else if (coin1 == "riyal" && coin2 =="dirham" ){
      result=0.98*amount;
      cout << result << "dirham";}

//dollar  
    
      else if(coin1=="dollar"&&coin2=="egyption_pound") {
       result=27.82*amount;
       cout<<result<<" egyption_pound";}
      else if (coin1 == "dollar" && coin2 == "euro" ) {
       result=1.15*amount;
      cout <<result<< " euro" ;}
       else if (coin1== "dollar" && coin2 == "riyal" ) {
       result=4.28*amount;
      cout << result << " riyal" ;}
      else if (coin1== "dollar" && coin2 == "dirham" ){
       result=4.44*amount;
      cout << result<< " dirham " ;}
      else if (coin1== "dollar" && coin2 == "won" ){
       result=1.56*amount;
      cout << result << " won " ;}
      else if (coin1== "dollar" && coin2 == "kuwaiti_pound" ){
       result=0.35*amount;
      cout << result << " kuwaiti_pound " ;}
      else if (coin1== "dollar" && coin2 == "sterling_pound" ){
       result=1.14*amount;
      cout << result<< " sterling_pound " ;}
      else if (coin1== "dollar"&& coin2== "franc" ){
       result=1.35*amount;
      cout << result << " franc " ;}
      
       //  dirham
  
     else if(coin1=="dirham"&&coin2=="egyption_pound"){
       result=0.98*amount;
       cout<<result<<"egyption_pound";}
      else if (coin1 == "dirham" && coin2 == "riyal" ){
       result=1.02*amount;
      cout <<result << "  riyal" ;}
     else if (coin1== "dirham"&& coin2 == "dollar"){
       result=0.27*amount;
      cout << result << "  dollar" ;}
     else if (coin1== "dirham"&& coin2 == "euro"){
       result=0.3*amount;
      cout << result << "  euro" ;}
      else if(coin1== "dirham"&& coin2 == "franc"){
       result=0.3*amount;
      cout << result << "  franc" ;}
      else if(coin1== "dirham" && coin2 == "kuwaiti_pound"){
       result=0.084*amount;
      cout << result << "  kuwaiti_pound" ;}
      else if(coin1 == "dirham" && coin2 == "won" ){
       result=372.94*amount;
      cout << result << "  won" ;}
      else if (coin1 == "dirham" && coin2 == "sterling_pound" ){
       result=0.27*amount;
      cout << result << "  sterling_pound" ;}
      
     // sterling_pound 
     
       else if(coin1=="sterling_pound"&&coin2=="egyption_pound"){
       result=27.82*amount;
       cout<<result<<"egyption_pound";}
      else if(coin1 == "sterling_pound" && coin2 == "riyal"){
       result=4.28*amount;
       cout<< result<< " riyal" ;}
      else if (coin1== "sterling_pound"&& coin2 == "dollar" ){
       result=1.14*amount;
      cout << result << "  dollar" ;}
      else if (coin1== "sterling_pound" && coin2 == "euro"){
       result=1,15*amount;
      cout <<result<< "euro" ;}
      else if(coin1== "sterling_pound" && coin2 == "franc" ){
       result=1.13*amount;
       cout <<result<< " franc" ;}
      else if (coin1 == "sterling_pound" && coin2 == "kuwaiti_dinar" ){
       result=0.35*amount;
      cout << result << " kuwaiti_dinar" ;}
      else if(coin1== "sterling_pound" && coin2 == "won" ){
       result=1.56*amount;
      cout << result << "    won" ;}
      else if (coin1 == "sterling_pound" && coin2 == "dirham" ){
       result=4.42*amount;
      cout << result<< "  dirham " ;}
      
      //euro 
      
      else if(coin1=="euro"&&coin2=="egyption_pound"){
       result=24.42*amount;
       cout<<result<<"egyption_pound";}
      else if(coin1 == "euro" && coin2 == "riyal" ){
       result=3.91*amount;
      cout <<result<< " riyal" ;}
      else if (coin1 == "euro" && coin2== "dollar" ){
       result=1.04*amount;
      cout <<result<< " dollar" ;}
      else if(coin1 == "euro" && coin2 == "franc" ){
       result=0.99*amount;
      cout << result<< "  franc" ;}
      else if (coin1== "euro" && coin2 == "kuwaiti_dinar" ){
       result=0.32*amount;
      cout << result << "  kuwaiti_dinar" ;}
      else if(coin1== "euro" && coin2== "won"){
       result=1.39*amount;
      cout << result << " won" ;}
      else if(coin1== "euro" && coin2 == "sterling_pound"){
       result=0.88*amount;
      cout << result << "  sterling_pound" ;}
      else if(coin1 == "euro" && coin2 == "dirham" ){
       result=3.82*amount;
      cout << result << "  dirham " ;}
      
   //franc

else if(coin1=="franc"&& coin2=="egyption_pound"){
      result=27.82*amount;
      cout<<result<<"egyption_pound";}
      else if(coin1== "franc" && coin2== "riyal" ){
       result=4.28*amount;
      cout << result<< " riyal" ;}
      else if (coin1== "franc" && coin2== "dollar" ){
       result=1.14*amount;
      cout << result<< "dollar" ;}
      else if(coin1== "franc" && coin2 == "euro" ){
       result=1.15*amount;
      cout << result<< "euro" ;}
      else if(coin1 == "franc" && coin2== "dirham" ){
       result=3.86*amount;
      cout << result<< " dirham";}
      else if(coin1== "franc" && coin2 == "kuwaiti_dinar" ){
       result=0.35*amount;
      cout << result<< "kuwaiti_dinar" ;}
      else if(coin1 == "franc" && coin2== "sterling_pound" ){
       result=0.89*amount;
      cout << result<< " sterling_pound " ;}
      else if(coin1 == "franc" && coin2== "won" ){
       result=1.39*amount;
      cout << result<< "won" ; }
      
      //kuwaiti_dinar
      
      else if(coin1=="kuwaiti_dinar"&&coin2=="egyption_pound"){
       result=78.98*amount;
       cout<<result<<"egyption_pound";}
     else if(coin1 == "kuwaiti_dinar" && coin2== "dirham" ){
       result=11.93*amount;
      cout << result << "  dirham " ;}
      else if(coin1 == "kuwaiti_dinar" && coin2 == "euro" ){
       result=3.25*amount;
      cout << result << " euro " ;}
      else if(coin1 == "kuwaiti_dinar" && coin2 == "dollar" ){
       result=3.23*amount;
      cout << result << " dollar " ;}
      else if(coin1== "kuwaiti_dinar" && coin2 == "sterling_pound" ){
       result=2.84*amount;
      cout <<result << " sterling_pound " ;}
      else if(coin1== "kuwaiti_dinar" && coin2 == "franc" ){
       result=3.25*amount;
      cout << result << " franc " ;}
      else if(coin1== "kuwaiti_dinar" && coin2 =="won" ){
       result=459.51*amount;
      cout <<result << " won " ;}
      else if (coin1 == "kuwaiti_dinar" && coin2 == "riyal" ){
      result=12.16*amount;
      cout <<result<< " riyal " ;}
      
      //won
      
      else if(coin1=="won" && coin2=="egyption_pound" ){
      result=0.018*amount;
      cout<<result<<" egyption_pound";}
      else if(coin1=="won" && coin2=="dollar" ){
      result=0.00075*amount;
      cout<<result<<"dollar";}
      else if(coin1=="won" && coin2=="riyal" ){
      result=0.0028*amount;
      cout<<result<<"riyal";}
      else if(coin1=="won" && coin2=="dinar" ){
      result=0.00023*amount;
      cout<<result<<"dinar";}
      else if(coin1=="won" && coin2=="euro" ){
      result=0.00072*amount;
      cout<<result<<"euro";}
      else if(coin1=="won" && coin2=="franc" ){
      result=0.00071*amount;
      cout<<result<<"franc";}
      else if(coin1=="won" && coin2=="dirham" ){
      result=0.0028*amount;
      cout<<result<<"dirham";}
      
      //error
      
      else{
        cout<<"  error...please enter another Coin";
      }
      return 0;
