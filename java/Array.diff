import java.util.ArrayList;
import java.util.List;

public class Kata {

  public static int[] arrayDiff(int[] a, int[] b) {
    // Your code here
    List<Integer> result = new ArrayList<>();
    for(int i: a){
      if(!contains(b,i)){
        result.add(i);
      }
    }
    
    return result.stream().mapToInt(Integer::intValue).toArray();
  }
  
  public static boolean contains(int[] array , int value){
    for(int i :array){
      if(i==value){
        return true;
      }
    }
    return false;
  }