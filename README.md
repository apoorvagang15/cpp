# Check for Binary
bool isBinary(string str)
{
   // Your code here
    
        int flag=0;
        for(int i=0;i<str.size();i++){
            if(str[i]!='1' && str[i]!='0'){
                flag++;
            }
        }
        if(flag>0){
            return 0;
        }
        return 1;
}

