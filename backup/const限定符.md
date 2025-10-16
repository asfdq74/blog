其作用与c中的#define相同，但const可在限定变量时声明其类型，但#define不行。
如：const int i=1
要注意，使用const限定时应在同一语句中为其指定数值，不可另起一行。
如：const int p；
        p=1：
这是不对的。