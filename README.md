
int main() {
  char s[80], sym;
  int count, i;
  system("chcp 1251");
  system("cls");
  printf("Введите строку: ");
  gets(s)
  sym = getchar();
  count = 0;
  for(i=0; s[i]!='\0'; i++)
  {
    if(s[i]==sym)
       count++;
  }
  printf("символ ");
  putchar(sym); // Вывод символа
  printf(" встречается %d раз",count);
  getchar(); getchar();
  return 0;
}
