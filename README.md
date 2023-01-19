public static List<Integer> reverseArray(List<Integer> a) {
    // Write your code here
    Collections.reverse(a);//2341
    List list=new ArrayList<>();
    for(int i=0;i<a.size();i++)
    {
        list.add(a.get(i));
    }
    return list;
    

    }

}
