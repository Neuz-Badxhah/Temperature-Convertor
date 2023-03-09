#include <stdio.h>
void far()
{
    int option;
    float far, celsius, kelvin;
    printf("Choose your option:\n");
    printf("1. Fehrenheit to celsius.\n");
    printf("2. Fehrenheit to kelvin.\n");
    printf("You choose:\t");
    scanf("%d", &option);
    end(1);
    if (option == 1)
    {
        // celsius to fahrenheit
        float celsius, far;
        printf("Enter the value of celsius temperature:\t\n");
        scanf(" %f", &celsius);
        printf("The celsius value is %.2f\n", celsius);
        far = celsius * 9 / 5 + 32;
        printf("The value of celsius temperature in fahrenheit is %.2f\n", far);
    }
    else
    {
        // kelvin to fahrenheit
        float Kelvin, far = 0;
        printf("Enter the value of celsius temperature:\t\n");
        scanf(" %f", &Kelvin);
        printf("The kelvin value is %.2f\n", Kelvin);
        far = (Kelvin - 273.15) * 9 / 5 + 32;
        printf("The value of kelvin temperature in fahrenheit is %.2f\n", far);
    }
    return 0;
}
void kelvin()
{
    int choose;
    float far, celsius, kelvin;
    printf("For fahrenheit choose 1\nFor celsius choose 2 \n");
    printf("You choose:\t");
    scanf("%d", &choose);
    end(1);
    if (choose == 1)
    {
        // fahrenheit to kelvin
        printf("Enter the value of far temperature:\t");
        scanf(" %f", &far);
        printf("The fahrenheit value is %.2f\n", far);
        kelvin = (far - 32) * 5 / 9 + 273.15;
        printf("The value of fahrenheit temperature in kelvin is %.2f\n", kelvin);
    }
    else
    {
        // celsius to kelvin
        printf("Enter the value of celsius temperature:\t");
        scanf(" %f", &celsius);
        printf("The celsius value is %.2f\n", celsius);
        kelvin = celsius + 273.15;
        printf("The value of celsius temperature in kelvin is %.2f\n", kelvin);
    }
}
void celsius()
{
    int Option;
    float far, celsius, kelvin;
    printf("Enter your option:\n");
    printf("1.  fahrenheit to celsius\n");
    printf("2.  Kelvin to celsius\n");
    printf("You choose:\t");
    scanf("%d", &Option);
    end(1);
    if (Option == 1)
    {
        // fahrenheit to celsius
        printf("Enter the value of fahrenheit temperature:\t");
        scanf("%f", &far);
        printf("The fahrenheit value is %.2f\n", far);
        celsius = (far - 32) * 5 / 9;
        printf("The value of fahrenheit in celsius is %.2f\n", celsius);
    }
    else
    {
        // kelvin to celsius
        printf("Enter the value of fahrenheit temperature:\t");
        scanf("%f", &kelvin);
        printf("The fahrenheit value is %.2f\n", kelvin);
        celsius = kelvin - 273.15;
        printf("The value of fahrenheit in celsius is %.2f\n", celsius);
    }
}
void end(int time)
{
    for (int i = 1; i <= time; i++)
    {
        printf("________________________\n");
    }
}
void main()
{
    int Choose;
    printf("Welcome to tempeture convertor\n");
    end(2);
label:
    printf("What do you want to change?\n");
    printf("1.  Fahrenheit\n");
    printf("2.  Kelvin\n");
    printf("3.  Celsius\n");
    printf("You choose:\t");
    scanf("%d", &Choose);
    end(1);
    switch (Choose)
    {
    case 1:
        far();
        end(1);
        break;
    case 2:
        kelvin();
        end(1);
        break;
    case 3:
        celsius();
        end(1);
        break;
    default:
        printf("Invalid Input. Please check your input.\n");
        goto label;
        break;
    }
    int cont;
    end(1);
    printf("Do yoy want to continue the system?\n");
    printf("To continue enter 1. Else enter anything.\n");
    scanf("%d", &cont);
    end(1);
    if (cont == 1)
     {
           system("cls");
           goto label;
     }
    else
    {
        end(1);
    }
    printf("Thank you!!! To use our system.\n");
    end(2);

    return 1;
}
