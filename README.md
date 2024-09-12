using System;
using System.Windows.Forms;

namespace DateEntryApp
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void displayButton_Click(object sender, EventArgs e)
        {
            string inputDate = inputTextBox.Text;
            outputTextBox.Text = inputDate;
        }
    }
}
