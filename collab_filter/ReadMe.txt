##############################
## Эͬ�����Ƽ�ģ��         ##
##############################


1. Introduction
    ���� Mahout �ܹ������ڳ������ṩ�Ƽ��������û� A �� B ������ȥĳ���򳡣��������򰮺��ߣ���� A �����˽���ĳ�����������Ʊ����ҲЭͬ�Ƽ��� B��

2. Usage
The input should be "item preference" pair, and at most it can accept 3 pairs. In the following example, "20590" is item id and "3.0" is its preference.The output is the "item preference" pair in string, and at most it could ouput 3 pairs.

Example:

char* input = "20590 3.0 98925 5.0 8587 2.0";
char* output = 0;

output = collab_filter(input);
printf("Result of collab_filter: %s\n", output);

Output:

Result of collab_filter: [RecommendedItem[item:121859, value:10.0], RecommendedItem[item:101384, value:10.0], RecommendedItem[item:66445, value:10.0]]
