# checkLepYear
this is to check whether entered year is a  Leap year or not
public class LeapYear {
    public static void main(String[] args) {
        int year = 1900;
        boolean leap = false;
        if(year % 4 == 0)
        {
            if( year % 100 == 0)
            {
                // year is divisible by 400, hence the year is a leap year
                if ( year % 400 == 0)
                    leap = true;
                else
                    leap = false;
            }
            else
                leap = true;
        }
        else
            leap = false;
        if(leap)
            System.out.println(year + " is a leap year.");
        else
            System.out.println(year + " is not a leap year.");
    }
}

hello guys
I want some changes from the code to shorten the code
