# test-0602
This is my tutorial repository.
##Example

###Related code :temp() in trap.c
`temp` is implemented as following code:

    void
    temp(void)
    {
        int fahr, celsius;
        int lower, upper, step;
  
        lower = 0;
        upper = 300;
        step = 20;
        fahr = lower;
  
        while (fahr <= uppeer) {
            celsius = 5 * (fahr-32) / 9;
            printf("%d\t%d\n",fahr, celsius);
            fahr = fahr + step;
        }
      }
