# BA II Professional

### A list of helpful tips & tricks:
 
* [Increasing/Decreasing Annuity](http://www.actuarialoutpost.com/actuarial_discussion_forum/showthread.php?t=48035#3) - This method is a bit of a hack and you still need to divide through by the interest rate.

* [Compound Growth Annuity](https://www.youtube.com/watch?v=sEB-SG82lSM) - Much like calculating a normal Annuity but with a clever  trick at *t=60s*.

* [Bond Spreadsheet](https://www.youtube.com/watch?v=y9Hhad_CAHg) - An example of calculating bond price `PRI` and accrued interest `AI` on a bond. Interest is accrued when the bond is sold between coupon payments. The BA II Plus uses the *Semi-Theoretical Method*.

![semi theoretical](https://github.com/Infinite-Actuary/BA-II-Plus-Professional/blob/master/images/semi-theoretical-method.png)

* [Format Settings](https://www.youtube.com/watch?v=OWajtj8ewn0) - Switch between Chain (`CHN`: operators are applied immediately with no precedence) and Algebraic Operating System (`AOS`: the expression is evaluated using [PEMDAS](https://en.wikipedia.org/wiki/Order_of_operations)).

* Calculating the modified duration of an annuity immediate.
> What is the modified duration of a 4 year annuity with level payments of $500 and 6% annual yield rate?

|     |               |                                                                                                             |
|-----|---------------|-------------------------------------------------------------------------------------------------------------|
| **SDT** | `1-01-2000`     |                                                                                                             |
| **CPN** | `9,999,999,999` | *use the largest number possible since coupon (CPN) is a percentage of redemption value (RV), which is zero.* |
| **RDT** | `1-01-2004`     |                                                                                                             |
| **RV**  | `0`             |                                                                                                             |
| **1/Y** |               |                                                                                                             |
| **YLD** | `6`             |                                                                                                             |
| **PRI** | **CPT** = 3.4651  | *a(4,0.06)*                                                                                                   |
| **DUR** | 2.2898        |   ⬅️ 🤓 💯                                                                                                          |
