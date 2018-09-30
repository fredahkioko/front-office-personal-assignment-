# front-office-personal-assignment-
Using GUI,create login,logout,charts

//this is a frame for the login page
public class PersonaAssignment {
     public static void main(String[] args) {
        JFrame myframe=new JFrame("Login Page");
        myframe.setSize(500,400);
        myframe.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        myframe.setVisible(true);}
        
       
      //this is the panels for the login page
      package personal.assignment;
package personal.assignment;
import java.awt.FlowLayout;
import javax.swing.JFrame;
import javax.swing.*;
s
public class PersonaAssignment {

    
    public static void main(String[] args) {
        JFrame myframe=new JFrame("Login Page");
        //to help with the arrangement of the panels
        JPanel mypanel=new JPanel(new FlowLayout());
        JLabel namelabel=new JLabel("User Name: ");
        JLabel passwordlabel=new JLabel("Password:");
        //this is where the names and passwords will be written
        JTextField username=new JTextField(10);
        JTextField password=new JTextField(15);
        JButton Login=new JButton("login");
        JButton Exit=new JButton("Exit");
        //we are adding panels into the frame
        mypanel.add(namelabel);
        mypanel.add(username);
        mypanel.add(passwordlabel);
        mypanel.add(password);
        mypanel.add(Login);
        mypanel.add(Exit);
        myframe.add(mypanel);
        myframe.setSize(500,400);
        myframe.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        myframe.setVisible(true);
        //to interact with user
        String Username;
    String Password;

    Password = "123";
    Username = "wisdom";

    Scanner input1 = new Scanner(System.in);
    System.out.println("Enter Username : ");
       Scanner input2 = new Scanner(System.in);
    System.out.println("Enter Password : ");
    if (username.equals(Username) && password.equals(Password)) {

        System.out.println("Access Granted! Welcome!");
    }

    else if (username.equals(Username)) {
        System.out.println("Invalid Password!");
    } else if (password.equals(Password)) {
        System.out.println("Invalid Username!");
    } else {
        System.out.println("Invalid Username & Password!");
    }
    //this is where the receptionist registers people
     import com.mysql.jdbc.Connection;
import com.mysql.jdbc.Statement;
import java.sql.SQLException;
public class userforms {
    private connection conn;
    private Statement statement;
    //this is the connection of java netbeans with xampp (mysql)
    public connection openConnection()throws SQLException
            
    { if (conn==null)
    { 
        String url="jdbc;mysql;//localhost/";
        String dbName="registration form";
        String driver="com.mysql.jdbc.Driver";
        String username="root";
        String password="";
        try
        {
            class.forName(driver);
            this.conn=(Connection)DriveMnager.getConnection(jdbc:mysql://localhost:3306/registration form?zeroDateTimeBehavior=convertToNull [root on Default schema]);
            
            system.out.println("REGISTER HERE");
        } 
        
        catch(ClassNotFoundException | SQLException sqle)
        {
      system.out.println("YOU CANNOT REGISTER HERE");
    }
    return conn;
    
        }
    }

    private void forName(String driver) {
        throw new UnsupportedOperationException("Not supported yet.");
        Database db =new Database();
          db.openConnection();//To change body of generated methods, choose Tools | Templates.
    }
    //code for the chart showing the chart statistics of gender
    import javax.swing.Frame;
    import org.Jfree.chart.ChartPanel;
    import org.Jfree.chart.JFreeChart;
    import org.Jfree.data.general.PieDataset;
    public class genderchart extends JFrame
    {
    public GenderChart(String apptitle,String chartTitle)
    {
    PieDataset dataset=createDataset();
    JFreeChart chart= createChart(dataset,chartTitle)
    ChartPanel chartPanel=new ChartPanel(chart);
    chartPanel.setPreferredsize(new java.awt.Dimension(500,300));
    setContentPane(chartPanel);
    }
    private PieDataset createdataset()
    DafaultPieDataset result= new DefaultPieDataset();
    result.SetValue("Male",65);
    result.SetValue("Female",65);
    return result;
    }
    Private JFreechart createchart(PieDataset dataset,string title)
    {
      JFreechart Chart=ChartFactory.createPiechart3D(title,dataset,true,true,false)
      p
      PiePlot3D plot=(PiePlot3D)chart.getPlot();
      plot.setStartAngel(0);
      plot.setDirection(Rotation.CLOCKWISE);
      plot.setForegroundAlpha(0.5f);
      return chart;
      public class MainChart
      {
      public static voidmain(string[]args)
      {
        creatChart cc=new CreateChart("Pie Chart Test","Gender comparison");
        cc.pack();
        cc.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        cc.setVisible(true);
       } 
   

        // TODO code application logic here
    
    
}
