# hello world
we are all about java,
the ambition is to help build an application that can 
help solve daily live issues
 below is an example of codes that calculates discount.
 
 import javax.swing.*;
 import java.awt.*;
 import java.awt.event.*;
 public class Discount extends JFrame{
    public Discounts(){
    JTextField f1 = new JTextField();
    JTextField f2 = new JTextField();
    JButton b1 = new JButton("Compute");
    JPanel p1 = new JPanel(new GridLayout(2,2));
    JPanel p2 = new JPanel();
    
    pq.add(new JLabel("AMOUNT");
    p1.add(f1);
    p1.add(new JLabel("DISCOUNT");
    p1.add(f2);
    p2.add(b1);
    
    setLayout(new BorderLayout());
    add(p1, BorderLayout.NORTH);
    add(p2, BorderLayout.SOUTH);
    
    
    }
   public static void main(String[]args){
     Discount frame = new Discoutn();
     frame.setTitle("Calculate Discount);
     frame.setVisible(true);
     frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
     frame.setLocationRelativeTo(null)
     frame.setSize(300,400);
     } 
   }
