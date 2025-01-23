# Matrix-addition

Coding-

package matrixaddition;
public class Matrixaddition{
    public static void main(String[] args) {
        //two-dimensional array
        int[][] matrixa={{1, 2, 3},{4, 5, 6}};
        int[][] matrixb={{7, 8, 9},{10, 11, 12}};
        int[][] result=new int[2][3];
        for(int i=0;i<matrixa.length;i++){
            for(int j=0;j<matrixa[i].length;j++){
                result[i][j]=matrixa[i][j]+matrixb[i][j];
            }
        }
        System.out.println("Resultant matrix after addition:");
        for (int[] row : result) {
            for (int element : row) {
                System.out.print(element+" ");
            }
            System.out.println();
        }
    }
    
}




Output-

Resultant matrix after addition:
8 10 12 
14 16 18 
