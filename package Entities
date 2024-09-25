package Entities;

public class Phone {
    private int id;
    private String lname;
    private String fname;
    private String pb;
    private String account;
    private int localct; // Час міських розмов (у хвилинах)
    private int intercityct; // Час міжміських розмов (у хвилинах)

    // Конструктор
    public Phone(int id, String lname, String fname, String pb, String account, int localct, int intercityct) {
        this.id = id;
        this.lname = lname;
        this.fname = fname;
        this.pb = pb;
        this.account = account;
        this.localct = localct;
        this.intercityct = intercityct;
    }

    // Методи get і set
    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public String getLastName() {
        return lname;
    }

    public void setLastName(String lname) {
        this.lname = lname;
    }

    public String getFirstName() {
        return fname;
    }

    public void setFirstName(String fname) {
        this.fname = fname;
    }

    public String getPatronymic() {
        return pb;
    }

    public void setPatronymic(String pb) {
        this.pb = pb;
    }

    public String getAccountNumber() {
        return account;
    }

    public void setAccountNumber(String account) {
        this.account = account;
    }

    public int getLocalCallTime() {
        return localct;
    }

    public void setLocalCallTime(int localct) {
        this.localct = localct;
    }

    public int getIntercityCallTime() {
        return intercityct;
    }

    public void setIntercityCallTime(int intercityct) {
        this.intercityct = intercityct;
    }

    // Метод toString для виведення інформації
    @Override
    public String toString() {
        return "Phone{" +
                "  id=" + id +
                " Прізвище='" + lname + '\'' +
                " Ім'я='" + fname + '\'' +
                " По батькові='" + pb + '\'' +
                " Номер рахунку='" + account + '\'' +
                " Час міських розмов=" + localct +
                " Час міжміських розмов=" + intercityct +
                '}';
    }
}
