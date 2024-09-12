using System;
using System.Windows.Forms;

namespace DateEntryApp
{
    public partial class Doc1: Form
    {
        public Doc1()
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
