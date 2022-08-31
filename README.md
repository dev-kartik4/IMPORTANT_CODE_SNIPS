# IMPORTANT_CODE_SNIPS

USE OF ENUMS

enum SUVS{
    scorpio(400),
    fortuner(500),
    endeavour(420),
    safari(380);
    final int torque;
    SUVS (int torque){
        this.torque = torque;
    }
}


public class Main{
    public static void main(String args[]){
        System.out.println("THE TORQUE OUTPUT OF SCORPIO IS "+SUVS.scorpio.torque+" NM ");
    }
}
