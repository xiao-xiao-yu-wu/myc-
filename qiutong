    int a[]= {1,2,4,5,5,6};
    int b[]= {4,5,6,7,8};
    int len_a = sizeof a/sizeof a[0];
    int len_b = sizeof b/sizeof b[0];
    int len_c;
    if (len_a >len_b)
    {
        len_c = len_b;
    }
    else
    {
        len_c = len_a;
    }
    int c[len_c];
    int index = 0;
    int biaoji =0;
    for (int j = 0;j<len_b;j++)
    {
        for (int i=0;i<len_a;i++)
        {
            if(b[j] == a[i])
            {
                biaoji =0;
                for (int k=0;k<index;k++)
                {
                    if (a[i] == c[k])
                    {
                        biaoji = 1;
                        cout<<"c数组中已经有"<<a[i]<<"了"<<endl;
                        break;
                    }
                }
                if (biaoji == 0)
                {
                    c[index] = a[i];
                    index++;
                }
            }
        }
    }
    for (int i=0;i<index;i++)
    {
        cout<<c[i]<<" ";
    }
