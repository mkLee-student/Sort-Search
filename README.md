# Sort-Search
# 자료구조 시간에 구현한 이진 탐색, 해시 탐색 / 삽입 정렬, 선택 정렬, 버블 정렬, 퀵 정렬, 합병 정렬입니다.
# 전체적으로 원본 배열을 변경시키지 않는 선으로 구현되어 있습니다.
# 비교함수의 경우 함수포인터를 매개변수로 받도록 해서 사용자가 원하는 비교함수를 넣어서 사용할 수 있습니다.
# 이진 탐색은 sorted list 에서만 사용가능하므로 bubble sort로 sorting 후 searching 합니다.
# 해시 탐색의 경우 매우 강력한 탐색능력이 있지만 데이터를 담을 공간이 많이 필요하다는 단점이 있습니다.
# 제가 구현한 해시 탐색의 해시 함수는 Modulo-Division을 활용하였습니다.
# Collision의 해결은 Linked list로 해결하였습니다.
#
# 정렬 알고리즘의 경우 한 소스파일과 헤더파일에 같이 정리되어 있습니다.
# 각 정렬 별로 수행시간도 [ms] 단위로 측정할 수 있도록 했는데, 데이터 갯수를 늘릴 수록
# 성능의 차이가 매우 현저하게 나는 것까지 확인하실 수 있습니다.
