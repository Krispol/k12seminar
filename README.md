# k12seminar

Java massiivide loomine ja kasutamine

andmetüüp peab olema massiivil määratud
massiivi suurus peab olema määratud


int[] myIntArray = new int[3];

int[] myIntArray = {1, 2, 3};

int[] myIntArray = new int[]{1, 2, 3}; - määrab dünaamiliselt massiivi pikkuse väärtuste põhjal
---------------------------------------------------------

String[] myStringArray = new String[3];

String[] myStringArray = {"a", "b", "c"};

String[] myStringArray = new String[]{"a", "b", "c"};


public class Massiiv1{
  public static void main(String[] arg){
    String[] eesnimed=new String[3];
    eesnimed[0]="Juku";
    eesnimed[1]="Kati";
    eesnimed[2]="Mati";
    for(int i=0; i<eesnimed.length; i++){
      System.out.println(eesnimed[i]);
    }
  }
}
