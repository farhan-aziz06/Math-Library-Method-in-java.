# Math-Library-Method-in-java.
Math Library Method in java.

        import java.util.Scanner;
        // Math Library...
        public class Libraries {
            public static void main(String[]args){
                Scanner console = new Scanner(System.in);

        //math.ulp Method....

       /*

       double a = 5.43;

        System.out.println(Math.ulp(a));
        System.out.println(Math.ulp(-a));

        double b = 0.0/0;
        System.out.println(Math.ulp(b));

        */

        //Math.toDegrees & Math.toRadians Method....

       /*

       double c = 180.53;

       int d = 180;

        System.out.println(Math.toRadians(c));
        System.out.println(Math.toRadians(d));

        double e = Math.PI/2;
        double f = Math.PI;

        System.out.println(Math.toDegrees(e));
        System.out.println(Math.toDegrees(f));

        */

        //  tanh(x) Method ....

        // Return hyperbolic tangent of a double value ...

        /*

        double a = 2.30;

        System.out.println(Math.tanh(a));

        int b = 2;

        System.out.println(Math.tanh(b));

        int c = 0;

        System.out.println(Math.tanh(c));

         */

        // tan(x) Method....

        /*

        int a = 3984;
        double z = Math.toRadians(a);

        System.out.println(Math.tan(z));

        double b = Math.toRadians(45.42);

        System.out.println(Math.tan(b));

        double c = 0;

        System.out.println(Math.tan(c));

         */

        // sqrt(x) Method...

       /*

        int a = 25;

        System.out.println(Math.sqrt(a));

        System.out.println(Math.sqrt(25.45));


        System.out.println(Math.sqrt(300));

        */

        // sinh(x) & sin(x) Method ...


        /*
        System.out.println(Math.sin(Math.toRadians(90)));

        System.out.println(Math.sin(1.0));

        System.out.println(Math.sin(0));



        System.out.println(Math.sinh(Math.toRadians(23.5)));

        System.out.println(Math.sinh(25));

        System.out.println(Math.sinh(0));

         */

        // signum(x)--------Return Sign of Number X

        /*

        System.out.println(Math.signum(-90.00));
        System.out.println(Math.signum(90.00));
        System.out.println(Math.signum(0.00));

         */


        // rint(x) Method in java... is an inbuilt method in Java which is used to round of the floating-point argument
        // to an integer value (in floating-point format).

        /*System.out.println(Math.rint(12.8));
        System.out.println(Math.rint(123));
        System.out.println(Math.rint(0.00));
        System.out.println(Math.rint(-2.17));

         */

        //round(x) Round Off number

        /*
        System.out.println(Math.round(5.4));
        System.out.println(Math.round(5.5));
        System.out.println(Math.round(5.8));
        System.out.println(Math.round(5.0));

         */

        // pow(x, y) 	Returns the value of x to the power of y

        /*

        System.out.println(Math.pow(3,2));
        System.out.println(Math.pow(3,2.5));
        System.out.println(Math.pow(3.4,2));
        System.out.println(Math.pow(3.4,2.2));

         */

        // nextUp(x) is a built-in math function in java which returns the floating-point value
        // adjacent to the parameter provided in the direction of positive infinity

        // System.out.println(Math.nextUp(4.378));

        // nextAfter(x, y)

        // System.out.println(Math.nextAfter(4,9));




        /*

        min(x, y) & max(x, y)

        System.out.println(Math.max(3,4));
        System.out.println(Math.max(-3,-2));
        System.out.println(Math.max(-3,0));

        System.out.println(Math.min(3,2));
        System.out.println(Math.min(3.4,2.2));
        System.out.println(Math.min(-3.4,0));

         */

        // log1p(x) return ka natural log of Base E
        /*
        System.out.println(Math.log1p(1));
        System.out.println(Math.log1p(5.4));
        System.out.println(Math.log1p(-22.4));
        //System.out.println(Math.log1p(-1/0));
        System.out.println(Math.log1p(0));
        System.out.println(Math.log1p(10));

         */

        //log10(x)  	Returns the base 10 logarithm of x

       /* System.out.println(Math.log10(10));
        System.out.println(Math.log10(1));
        System.out.println(Math.log10(0));
        System.out.println(Math.log10(10.2));

        */

        //log(x)  Returns the natural logarithm (base E) of x

        /*System.out.println(Math.log(10));
        System.out.println(Math.log(0));
        System.out.println(Math.log(0.333));
        System.out.println(Math.log(-0.333));
        System.out.println(Math.log(33.333));

         */

        // IEEEremainder(x, y) Computes the remainder operation on x and y as prescribed by the IEEE 754 standard

        // System.out.println(Math.IEEEremainder(20,4));

        // hypot() Return Values returns Math.sqrt(x2 + y2)

        // System.out.println(Math.hypot(3,4));

        //getExponent(x) Returns the unbiased exponent used in x

        //System.out.println(Math.getExponent(-89.9));

        //floor(x) 	Returns the value of x rounded down to its nearest integer

       /* System.out.println(Math.floor(3.2));
        System.out.println(Math.floor(3.5));
        System.out.println(Math.floor(3.6));
        System.out.println(Math.floor(-3.6));

        */

        //expm1(x) 	Returns epowerx -1

        /*System.out.println(Math.expm1(3.2));
        System.out.println(Math.expm1(3));
        System.out.println(Math.expm1(0));
        System.out.println(Math.expm1(-2));
        System.out.println(Math.expm1(-2.32));

         */

        // exp(x) 	Returns the value of Ex

       /* System.out.println(Math.exp(23));
        System.out.println(Math.exp(2.3));
        System.out.println(Math.exp(-2.3));
        System.out.println(Math.exp(-23));
        System.out.println(Math.exp(-0));

        */

        // copySign(x, y) 	Returns the first floating point x with the sign of the second floating point y

        /*System.out.println(Math.copySign(3,2));
        System.out.println(Math.copySign(3,-2));
        System.out.println(Math.copySign(3,0));
        System.out.println(Math.copySign(-10,-1));

         */

        // ceil(x) 	Returns the value of x rounded up to its nearest integer

        /*
        System.out.println(Math.ceil(3.2));
        System.out.println(Math.ceil(3.0));
        System.out.println(Math.ceil(-3.22));

         */

        // cbrt(x) 	Returns the cube root of x

        /*

        System.out.println(Math.cbrt(4));
        System.out.println(Math.cbrt(3.3));
        System.out.println(Math.cbrt(0));
        System.out.println(Math.cbrt(-9));
        System.out.println(Math.cbrt(8));

         */

        // abs(x) 	Returns the absolute value of x

        /*
        System.out.println(Math.abs(-2));
        System.out.println(Math.abs(0));
        System.out.println(Math.abs(9.2));
        System.out.println(Math.abs(-9.2));

         */

        //The arc cosine is the inverse of the cosine function.

        //acos(x) 	Returns the arccosine of x, in radians ; asin(x) 	Returns the arcsine of x, in radians ;
        //atan(x) 	Returns the arctangent of x as a numeric value between -PI/2 and PI/2 radians...
        //atan2(y,x) 	Returns the angle theta from the conversion of rectangular coordinates (x, y) to polar coordinates (r, theta).

        /*
        System.out.println(Math.acos(0.98));
        System.out.println(Math.asin(0));
        System.out.println(Math.atan(60.88));

        System.out.println(Math.atan2(0.6,7));

         */
        /*.Exact Methods
                

        // .addExact()
        System.out.println(Math.addExact(2,3));
        System.out.println(Math.addExact(2,-3));

        // .subtractExact
        System.out.println(Math.subtractExact(25,-8));

        //toIntExact
        System.out.println(Math.toIntExact(344241441L));

        //
        System.out.println(Math.negateExact(-4248999));
        
         */









    }
}

