# FloatAndDouble
Lesson on Floats and Doubles
package com.JohnHay;

public class Main {

    public static void main(String[] args) {
	    // width of an interger = 32 (4 bytes)
        int myIntValue = 5 / 3;
	    // width of a float = 32 (4 bytes)
        float myFloatValue = 5f / 3f;
	    // width of double = 64 (8 bytes)
        double myDoubleValue = 5d / 3d;

        System.out.println("myIntValue = " + myIntValue);
        System.out.println("myFloatValue = " + myFloatValue);
        System.out.println("myDoubleValue = " + myDoubleValue);

        double myPoundsValue = 200;
        double convertedKilograms = myPoundsValue * 0.45359237;

        System.out.println("Total KGs = " + convertedKilograms);
        // 90.7185
        double pi = 3.141_592_7d;  //example use _ to make reading numbers easier when using literals 



    }
}
