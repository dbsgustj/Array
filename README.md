# Array
# 자바로 구별하는 배열 알고리즘
# 설명
2개의 배열을 비교해보고 다르다면 fales 라는 데이터를 변환하고 함수를 종료하게된다.
배열의 크기가 같으면 반복문을 통하여 2배열의 각각 인덱스가 같은지 비교하여 다르다면 fales 라는 데이터를 변환하고 종료하게 된다.
마지막까지 다르지 않고 같다면 TRUE 라는 데이터를 변환하고 종료하게 된다.
# 자바 코드
	static boolean equals(int[] a, int [] b ) {
		if(a.length != b.length)
			return false;
      
		for(int i = 0; i < a.length; i++) 
			if(a[i]!=b[i])
			
      return false;
		
    return true;
