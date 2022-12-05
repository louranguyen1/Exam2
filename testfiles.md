Notes: what my testfiles include. They are all in .txt form

file1:

public class Main {
	public static void main(String[] args) {
		String a = "a";
		int i = 3;
	}
}


file2 (syntax error)

public class Main {
    public static void main String[] args) {
        String a = a";
        int i = 3;
        String b = c";
        System.out.println("yes);
    }

Errors:
1) missing ( after main
2) missing " before a
3) missing " before c
4) missing " after yes
5) missing } at the end


file3 (lexical error)

public class Main {
    public static void main (String[] args) {
        int 3a = 3;
        String 1a = "yes";
        String 9a = "no";
        int 1b = 5;
        int 0x = 1;
    }
}

Errors:
1) 3a - identifier can't start with a number
2) 1a - identifier can't start with a number
3) 9a - identifier can't start with a number
4) 1b - identifier can't start with a number
5) 0x - identifier can't start with a number


file4

public class main {
	public static void main(String[] args) {
		String a = "this is a correct file with no errors";
		String b = "moving on to the next file";
		int sum = 0;
		sum++;
	}
}
