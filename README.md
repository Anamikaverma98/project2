# project2
 public static void main(String[] args) {
        int min,year,day;
        Scanner input= new Scanner(System.in);
        System.out.print("Enter the number of minutes");
         min= input.nextInt();
         year = min / 525600;
         min = min%525600;
         day = min / 1440;
         min = min% 1440;        
        
        System.out.println("No. of year"+year);
        System.out.println("No. of days"+day);
    }
    
} 
