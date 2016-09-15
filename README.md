# HashMap
coreJava-session9Assignment3
epackage comm.collection.classes;

import java.util.HashMap;
import java.util.Iterator;

public class mapExample {
public static void main(String[] args) {
	
	String name1=new String("chaitanya");
	String name2=new String("krishna");
	String name3=new String("rakesh");
	String name4=new String("advaitha");
	

	
	Integer id1= new Integer("123");
	Integer id2= new Integer("124");
	Integer id3= new Integer("125");
	Integer id4= new Integer("126");
	
	HashMap<Integer, String> Empcode=new HashMap<Integer, String>();
	Empcode.put(id1,name1);
	Empcode.put(id2,name2);
	Empcode.put(id3,name3);
	Empcode.put(id4,name4);
	
	System.out.println(Empcode);
	System.out.println(Empcode.get(id1));
	System.out.println(Empcode.get(id2));
	System.out.println(Empcode.get(id3));
	System.out.println(Empcode.get(id4));
	 }
	
	
}

