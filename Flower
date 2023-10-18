import java.awt.*;
import javax.swing.*;
public class Draw_Flower extends JPanel {
  public static void main(String[] args) {
    JFrame frame = new JFrame("Flower");
    frame.setSize(500, 500);
    frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
    JPanel flower = new Flower();
    flower.setBackground(Color.white);
    frame.add(flower);
    frame.setVisible(true);
  }
@Override
  public void paintComponent(Graphics g) {
    super.paintComponent(g); 
    Graphics2D g2 = (Graphics2D) g;
    g2.setStroke(
    new BasicStroke(10, BasicStroke.CAP_ROUND, BasicStroke.JOIN_ROUND));
    g2.setColor(new Color(0, 128, 0)); 
    g2.drawLine(toScreenX(100), toScreenY(190), toScreenX(100), toScreenY(70));
    g2.setColor(new Color(255, 165, 0));  
    g2.fillOval(toScreenX(75), toScreenY(45), toScreenX(50), toScreenY(50));
    int petalWidth = toScreenX(20);
    int petalHeight = toScreenY(20);
    g2.setColor(new Color(255, 192, 203));  
    g2.fillOval(toScreenX(90), toScreenY(35), petalWidth, petalHeight);
    g2.fillOval(toScreenX(90), toScreenY(85), petalWidth, petalHeight);
    g2.fillOval(toScreenX(64), toScreenY(60), petalWidth, petalHeight);
    g2.fillOval(toScreenX(115), toScreenY(60), petalWidth, petalHeight);
    g2.fillOval(toScreenX(108), toScreenY(78), petalWidth, petalHeight);
    g2.fillOval(toScreenX(108), toScreenY(42), petalWidth, petalHeight);
    g2.fillOval(toScreenX(72), toScreenY(78), petalWidth, petalHeight);
    g2.fillOval(toScreenX(72), toScreenY(42), petalWidth, petalHeight);
  }
  private int toScreenX(int x) {
    return Math.round(x * getWidth() / 200f);
  }
  private int toScreenY(int y) {
    return Math.round(y * getHeight() / 200f);
  }
}
