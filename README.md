# study
study project




package kr.co.moak.finalprj;

import java.awt.Color;   //		f.getContentPane().setBackground(Color.YELLOW);
import javax.swing.JFrame;    //JFrame f = new JFrame();

public class ClothUI{   

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		JFrame f = new JFrame();  //f직원을 부름
		f.setTitle("옷관리");
		f.setSize(400, 300);
		f.getContentPane().setBackground(Color.YELLOW);

		f.setVisible(true); //보여주기
	}

}
