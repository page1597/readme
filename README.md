# readme
<H2>public static void main()</H2>
초기 데이터(data), 클러스터의 개수(noofcluster), 중심점(centroid)를 설정해 준다.
getCentroid 메소드를 호출한다.
<H2>public static int[][] getCentroid()</H2>
중심점(centroid)을 찾는다.
각 데이터별로 현재 중심점으로부터의 거리를 구한다.
각 중심점에서 거리가 가까운 데이터끼리 clustering하여 C1, C2, C3를 출력한다.
C1, C2, C3에서의 새로운 중심점(centroid)을 구한다.
새로운 중심점을 기준으로 다시 clustering한다.
이전 중심점과 현재 중심점이 같을 때(optimization)까지 반복한다. 
최종적으로 clutstering된 cluster를 출력한다.
