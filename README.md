# chenfeng123456
my code
int numJewelsInStones(char* J, char* S) {
    int Jsize=strlen(J);
    int Ssize=strlen(S);
    int amount=0;
    for(int i=0;i<Ssize;i++)
    {
        for(int k=0;k<Jsize;k++)
        {
            if(S[i]==J[k]) amount++;
        }
    }
    return amount;
}
