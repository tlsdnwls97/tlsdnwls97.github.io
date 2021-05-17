# tlsdnwls97.github.io

# 5-17일자 test 1번 풀이 

package ex.java.input;

public class InputTest11 {

	public static void main(String[] args) {
		
		//첫번째 방법 (소숫점 나오는 방법)
		
		int a = 10;
		int b = 25;
		int c = 33;
		
		int Num1 = a + b + c;
		double Num2 = Num1 / 3.0;
		
		System.out.println(Num1);
		System.out.println(Num2);
		
		/* ------------------------------------ */
		
		//두번째 방법 (소숫점 안나오는 방법)
		
		int oneScore = 10;
		int twoScore = 25;
		int threeScore = 33;
		
		int totalScore = oneScore + twoScore + threeScore;
		System.out.println(totalScore);
		
		double avgScore = totalScore / 3;
		System.out.println(avgScore);

	}

}
