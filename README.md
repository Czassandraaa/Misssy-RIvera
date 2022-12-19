# Misssy-RIvera
{
    float numOne, numTwo, res;
    int choice;
    do
    {
        cout<<"1. Addition\";
        cout<<"2. Subtraction\";
        cout<<"3. Multiplication\";
        cout<<"4. Division\";
        cout<<"5. Exit\\";
        cout<<"Enter Your Choice(1-5): ";
        cin>>choice;
        if(choice>=1 && choice<=4)
        {
            cout<<"\Enter any two Numbers: ";
            cin>>numOne>>numTwo;
        }
        switch(choice)
        {
            case 1:
                res = numOne+numTwo;
                cout<<"\Result = "<<res;
                break;
            case 2:
                res = numOne-numTwo;
                cout<<"\Result = "<<res;
                break;
            case 3:
                res = numOne*numTwo;
                cout<<"\Result = "<<res;
                break;
            case 4:
                res = numOne/numTwo;
                cout<<"\Result = "<<res;
                break;
            case 5:
                return 0;
            default:
                cout<<"\Wrong Choice!";
                break;
        }
        cout<<"\------------------------\";
    }while(choice!=5);
    cout<<endl;
    return 0;
}
