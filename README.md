# Time_changes
#include <iostream>
using namespace std;

int main() {
	unsigned long t;
	int p[12][60];
	cin>>t;
	int a;
	 for(int l=0;l<12;l++)
	    {
	        for(int m=0;m<60;m++)
	        {	 cout<<"\n j="<<l<<"  k= "<<m;
	    }
	            /*int hour_angle=((60*l)+m)*0.5;
	            int min_angle=6*m;
	            int angle;
	           
	            if(hour_angle>min_angle)
	            {
	                angle=hour_angle-min_angle;
	            }
	            else
	            {
	                angle=min_angle-hour_angle;
	            }
	            if((360-angle)<angle)
	            {
	                angle=360-angle;
	            }
	            p[l][m]=angle;
	           cout<<"\np["<<l<<"]["<<m<<"]  ="<<p[l][m];
	        }
	    }
	for(int i=0;i<t;i++)
	{
	    cin>>a;
	    cout<<"  \na="<<a;
	   for(int j=0;j<12;j++)
	   {
	       for(int k=0;k<60;k++)
	       {
	           if(p[j][k]==a)
	           {    cout<<"  matched ";
	               if(j>9)
	               {
	                   cout<<j<<":";
	               }
	               else
	               {
	                   cout<<"0"<<j<<":";
	               }
	               if(k<10)
	               {
	                   cout<<"0"<<k;
	               }
	               else
	               {
	                   cout<<k;
	               }
	               cout<<"\n";
	           }
	       }
	   }*/
	    
	}
	return 0;
}

