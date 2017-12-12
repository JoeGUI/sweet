 public static void printArray(String message, int a[])  {
        //数组打印
        System.out.println(message);
        for (int i = 0; i < a.length; i++) {
            System.out.print(a[i]+"，");
        }

        System.out.println();
    }






public static void joinArray(int[] a, int[] b) {
            //合并两个数组
            List<Integer> list = new ArrayList<>();
            for (int i = 0; i < a.length; i++) {
                list.add(a[i]);

            }
            for (int i = 0; i < b.length; i++) {
                list.add(b[i]);

            }    
            System.out.println("合并后的数组：");
            for (Integer integer : list) {
                System.out.print(integer+" ");
            }
            System.out.println();
        }