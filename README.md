# Peremeshat
def shuffle_array(arr):
    p = 1
    q = len(arr)
    if q % 2 == 0:
        q -= 1
    while p < q:
        arr[p], arr[q] = arr[q], arr[p]
        p += 2
        q -= 2
    for number in arr:
    	print(number, end=' ')
shuffle_array([1, 1, 1, 1, 1, 1])
