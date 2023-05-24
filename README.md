
class Main {
  public static void main(String[] args) {

    String str = "kajak";
    String odwroconyStr = "";
    
    

    for (int i = str.length() - 1; i >=0; --i) {
      odwroconyStr = odwroconyStr + str.charAt(i);
    }

    if (str.toLowerCase().equals(reverseStr.toLowerCase())) {
      System.out.println(str + " .");
    }
    else {
      System.out.println(str + " nie jest palindromem");
    }
  }
}
