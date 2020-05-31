# string-permutation
  Using namespace srd;
Void permute(strings,intl,intr)
{
  If(l==r)
   Count<<a<<endl;
  else
   {
     For(inti=1;i<=r;I++)
      {
        Swap(a[1],a[I]);
        Permute(a,1+I,r);
        Swap(a[1],a[I]);
      }
int main()
{
   String str="ABC";
   int n=str.size();
   Permute (str,0,n-1);
   Return0;
}
