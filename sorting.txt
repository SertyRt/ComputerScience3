public void selectionSort(int[] a){
	for (int k = 0; k < a.length-1; k++) {
		int j = k;
		for (int q = k+1; q < a.length; q++){
			if (a.[j] > a[q]){
				j = q;
			}
		}
		swap(a, k, j);
	}
}
