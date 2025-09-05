# 🔁 Iterative Waterfall Model

## 1. **What is it?**

* It’s an **improved version of the Classic Waterfall Model**.
* Still follows **step-by-step phases** (like Waterfall),
* BUT allows **feedback and iteration** → you can go back to previous stages if needed.
* This makes it **less rigid** and more practical.

---

## 2. **Phases (with Example)**

Let’s take the example of making a **Banking App** 🏦.

1. **Requirement Analysis**

   * Gather requirements: login, check balance, transfer money.

2. **System Design**

   * Create blueprint: database (customers, accounts, transactions), UI design.

3. **Implementation (Coding)**

   * Write code for login, balance check, transfer.

4. **Testing**

   * Test login and transactions.
   * Suppose you find a **bug in balance calculation** → go back to **Design/Coding**.

5. **Deployment**

   * Launch app for real users.

6. **Maintenance**

   * Add new features like **mobile recharge, bill payment** later.
   * If issues come, you iterate back to analysis/design.

---

## 3. **Text Visualization of Iterative Waterfall Model**

```
   +-------------------------+
   | 1. Requirement Analysis |
   +-------------------------+
               |
               v
   +-------------------------+
   |     2. System Design    |
   +-------------------------+
               |
               v
   +-------------------------+
   | 3. Implementation (Code)|
   +-------------------------+
               |
               v
   +-------------------------+
   |       4. Testing        |
   +-------------------------+
               |   ^
               |   |
               v   |
   +-------------------------+
   |     5. Deployment       |
   +-------------------------+
               |
               v
   +-------------------------+
   |     6. Maintenance      |
   +-------------------------+
               ^
               |
        (Feedback Loops –
      go back if changes needed)
```

👉 Unlike the **Classic Waterfall (one-way flow)**, here you see **feedback loops** (you can move backward).

---

# 🔁 Iterative Waterfall Model – Advantages & Disadvantages

## ✅ Advantages

1. **Flexibility over Classic Waterfall**

   * Allows going back to previous phases if errors/changes are found.
   * Example: If testing finds a bug, developers can return to design/coding phase.

2. **Early Error Detection**

   * Problems can be fixed earlier instead of waiting until the very end.
   * Saves time and cost compared to classic waterfall.

3. **Improved Quality**

   * Because feedback loops exist, the product is more reliable and better tested.

4. **Client Satisfaction**

   * Since feedback can be incorporated during development, clients get what they want more accurately.

5. **Documentation Support**

   * Like classic waterfall, it still has proper documentation, which helps in large teams.

6. **Good for Medium-Sized Projects**

   * Suitable when requirements are mostly clear but may need minor refinements during development.

7. **Less Risk than Classic Waterfall**

   * The chance of project failure reduces because errors can be corrected before moving too far.

---

## ❌ Disadvantages

1. **Still Linear at Core**

   * Though feedback is allowed, it still mainly follows a **step-by-step sequence**.
   * Major requirement changes are still hard to handle.

2. **Time-Consuming**

   * Iterations (going back) take extra time, so projects can take longer.

3. **Higher Cost than Classic Waterfall**

   * More testing + rework increases cost.

4. **Not Ideal for Highly Changing Requirements**

   * If requirements change frequently (like in startups or modern apps), Agile is better.

5. **Heavy Documentation**

   * Each phase still requires documentation, which slows down the process.

6. **Complex Management**

   * Keeping track of iterations and changes adds complexity.

7. **Delayed User Feedback**

   * Unlike Agile (where users see working software early), in Iterative Waterfall, the client still waits until later stages to see the product.