#include<stdio.h>
#include<conio.h>
#include<math.h>
#include<string.h>
#define MAXSIZE 200
void Nhapmang(int a[], int &n);
void Xuatmang(int a[], int n);
void Xuat_SoLe(int a[], int n);
void Xuat_ViTriSoLe(int a[], int n);
void DaoMang(int a[], int n);
void menu()
{
	printf("\nbai 1");
	printf("\nbai 2");
	printf("\nbai 3");
	printf("\nbai 4");

}
void main()
{
	int A[MAXSIZE], N, chon;
	do
	{
		printf("chon bai");
		scanf_s("%d", &chon);
		switch (chon)
		{
		case 1:
		{
				  Nhapmang(A, N);
				  printf("\n Noi dung cua mang la:\n ");
				  Xuatmang(A, N);
		}
			break;

		case 2:
		{
				  Nhapmang(A, N);
				  printf("\n noi dung cua mang vua tao la: ");
				  Xuatmang(A, N);
		}
			break;

		case 3:
		{
				  Nhapmang(A, N);
				  Xuat_SoLe(A, N);
		}
			break;

		case 4:
		{
				  Nhapmang(A, N);
				  DaoMang(A, N);

		}
			break;

		case 5:
		{
            
		}


		}
	} while (chon != 0);
	_getch();
}

void Nhapmang(int a[], int &n)
{
	do
	{
		printf("cho biet phan tu cua mang: ");
		scanf_s("%d", &n);
	} while (n <= 0);
	for (int i = 0; i < n; i++)
	{
		printf("gia tri phan tu cua a[%d]: ", i);
		scanf_s("%d", &a[i]);
	}
}

void Xuatmang(int a[], int n)
{
	for (int i = 0; i < n; i++)
		printf("%4d", a[i]);
}

/*void Xuat_SoLe(int a[], int n)
{
	int dem;
	dem = 0;
	for (int i = 0; i < n; i++)
	if (a[i] % 2 != 0)
		printf("\nmang so le la %d", a[i]); 
} */
void Xuat_ViTriSoLe(int a[], int n)
{
	int dem;
	dem = 0;
	for (int i = 0; i < n; i++)
	if (a[i] % 2 != 0)
		printf("\n mang so le la a[%d]=%d", i, a[i]);
}
void DaoMang(int a[], int n)
{
	for (int i = 0; i < n; i++)
		int tam = a[i];
	a[i] = a[n - i - 1];
	a[n - 1 - i] = tam;
}

