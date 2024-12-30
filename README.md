# string-palindrome

String t="mom";
       String b="";
       String a=t;
       for(int i=a.length()-1;i>=0;i--)
       {
           b=b+a.charAt(i);
           
       }
       //System.out.println(b);
      if(a.equals(b))
      {
          System.out.println("palindrome");
      }
      else
      {
          System.out.println("not palindrome");
      }
