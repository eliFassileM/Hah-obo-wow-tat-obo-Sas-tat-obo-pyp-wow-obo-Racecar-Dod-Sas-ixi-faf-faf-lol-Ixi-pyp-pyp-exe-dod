Anagram palendrome analogy/ synonym so words letters do/don't flip/nonflip..a/ axa b/ bab c/cac d/Dod e/eqe f/faf g/ gag h/ hah i/ ixi j/ Jaj k/ Kyk L/ lol m/ Mym n/ non o/ obo p/ pyp q/ Qaq r/ racecar s/ Sas t/ tat u/ uxu v/ Vav w/ wow x/ Xanax™ y/ yay z/ zaz
double val = 1.00;
        for (int i = 0; i < 10; i++) {
            val += 0.10;
        }
        System.out.println(val); // 2.000000000000001

        double first = 0.1;
        double second = 0.2;
        double result = first + second;
        System.out.println(result); // 0.30000000000000004

        double a = 1.0000001;
        double b = 2.0000002;
        double c = 3.0000003;

        System.out.println((a + b) + c); // 6.0000006
        System.out.println(a + (b + c)); // 
BigDecimal val = new BigDecimal("1.00");
        for (int i = 0; i < 10; i++) {
            val = val.add(new BigDecimal("0.10"));
        }
        System.out.println(val); // 2.00

        BigDecimal first = new BigDecimal("0.1");
        BigDecimal second = new BigDecimal("0.2");
        BigDecimal result = first.add(second);
        System.out.println(result); // 0.3

        BigDecimal a = new BigDecimal("1.0000001");
        BigDecimal b = new BigDecimal("2.0000002");
        BigDecimal c = new BigDecimal("3.0000003");

        System.out.println((a.add(b)).add(c)); // 6.0000006
        System.out.println(a.add(b.add(c))); // 6.0000006
        System.out.println(new BigDecimal(0.35)); // 0.34999999999999997779553950749686919152736663818359375
System.out.println(new BigDecimal("

BigDecimal amount = new BigDecimal("15000.99");
        NumberFormat usFormat = NumberFormat.getCurrencyInstance(Locale.US);
        System.out.println(usFormat.format(amount)); // $15,000.99

        NumberFormat franceFormat = NumberFormat.getCurrencyInstance(Locale.FRANCE);
        System.out.println(franceFormat.
        public class Money {
    private BigDecimal amount; // or long if you want to operate on minor units
    private Currency currency;

    // methods like add/substract/multiply/allocate
    // utility methods for comparison: eq, gt, gte, lt, lte ...
    // currency check in every method
    // formatting logic


FastMoney m = FastMoney.of(200.20, "USD");
Money m2 = Money.of(200.20, "USD");
       
