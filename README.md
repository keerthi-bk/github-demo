# github-demo
A simple git-hub demo repository to show git_hub work flow
this is my first comit
# to maximum area in a 2D matrics Java
public int Max_Area(int []matrix)
{   
     int max=0;
     for(int i=0; i<matrix.length; i++){
      for(int j=0; j<Matrix[0].length; j++){
      if(matrix[i][i]==1){
      matrix[i][j]=1+Math.min(Math.min(matrix[i-1][j],matrix[i-1][j-1]),matrix[i][j-1]);
      max=Math.max(matrix[i][j],max);
      }
      }
      return max;
     }
}
