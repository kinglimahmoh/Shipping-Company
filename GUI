import tkinter as tk

class ShippingCompanyGUI:
    def __init__(self, root):
        self.root = root
        self.root.title("Shipping Company")

        self.sender_label = tk.Label(root, text="Sender")
        self.sender_entry = tk.Entry(root)
        self.recipient_label = tk.Label(root, text="Recipient")
        self.recipient_entry = tk.Entry(root)
        self.weight_label = tk.Label(root, text="Weight (kg)")
        self.weight_entry = tk.Entry(root)
        self.submit_button = tk.Button(root, text="Submit", command=self.submit)

        self.sender_label.grid(row=0, column=0)
        self.sender_entry.grid(row=0, column=1)
        self.recipient_label.grid(row=1, column=0)
        self.recipient_entry.grid(row=1, column=1)
        self.weight_label.grid(row=2, column=0)
        self.weight_entry.grid(row=2, column=1)
        self.submit_button.grid(row=3, column=0, columnspan=2)

    def submit(self):
        sender = self.sender_entry.get()
        recipient = self.recipient_entry.get()
        weight = self.weight_entry.get()
        print("Sender:", sender)
        print("Recipient:", recipient)
        print("Weight:", weight)

root = tk.Tk()
app = ShippingCompanyGUI(root)
root.mainloop()

