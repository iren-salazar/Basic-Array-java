# Basic-Array-java
Studying basic array in java



package studyArrays;

public class SingleArr {
	public static void main(String[] args) {
		
		String [] friends = {"Nike", "Mike", "Drake"};
		
		//prints [Ljava.lang.String;@2626b418
		System.out.println(friends);
		// print 3
		System.out.println(friends.length);
		// prints Nike
		System.out.println(friends[0]);
		// casting
		friends [1] = "Sofia";
		friends [0] = "Joy";
		friends [2] = "Miah";
		System.out.println("----------");
		
		System.out.println(friends[0]);
		System.out.println(friends[1]);
		System.out.println(friends[2]);
	}
}
