# How To Order PCBs

All the PCB Gerber files and corresponding BOMs are included in the **Electrical Hardware** folder. You can order the PCBs from any fabrication house of your preference. I usually use JLCPCB, and if you opt to use them, here's a guide to help you place your order. The process is quite similar across most other PCB fabrication services.

---

## Before You Start: Verify Your Gerber Files

It's good practice to visually inspect your Gerber files before uploading them to a fab house. Use a free online viewer to make sure all layers look correct:

- [Tracespace Viewer](https://tracespace.io/view/) — great for layer-by-layer inspection
- [JLCPCB Gerber Viewer]([https://gerber-viewer.jlcpcb.com](https://jlcpcb.com/RGE)) — shows exactly how JLCPCB will interpret your files

---

## Step 1: Create an Account on JLCPCB

1. Visit the [JLCPCB website](https://jlcpcb.com).
2. Sign up for a free account if you don't already have one.
3. Log in to access the ordering interface.

---

## Step 2: Upload the Halo Gerber Files from this GitRepo, [here](https://github.com/BlueMustrad/AeroBrick/tree/main/PCBs%20and%20Circuitry)

1. On the JLCPCB homepage, drag and drop the Halo Gerber file package into the **"Add Gerber file"** container.

> 💡 JLCPCB accepts `.zip` files, keep your Gerbers zipped, don't upload individual files.

---

## Step 3: Configure Your PCB Options

Once the Gerber files are uploaded, customize the PCB specifications:

### Basic Options

| Option | Value |
|--------|-------|
| Layer Count | 2 (both AeroBrick PCBs are 2-layer) |
| Dimensions | Auto-detected from the Gerber files |
| Quantity | Choose the number of PCBs you need |
| Thickness | 1.6mm (recommended) |
| Material | FR4 |

### Advanced Options

| Option | Value |
|--------|-------|
| Solder Mask Color | Pick any color you prefer |
| Silkscreen Color | White or black (depending on solder mask) |
| Surface Finish | Your preference, I usually do Lead Free HASL |
| Via Options | Tenting |

> Leave all other options as default.

---

## Step 4: Review Pricing and Shipping Costs

JLCPCB provides a real-time cost estimate based on your selected options. Make sure to review:

- PCB production costs
- Shipping options and costs

Shipping options include DHL, FedEx, and standard post. Choose one based on your budget and urgency.

> 💡 **Pro Tip:** JLCPCB frequently offers new-user coupons that bring 5 PCBs down to $2/5. Check their promotions page before checking out.

---

## Step 5: Add Additional Services (Optional)

JLCPCB offers additional services, such as:

- **SMT Assembly:** if you need components assembled on your board
- **Solder Stencil:** for solder paste application during assembly

If required, configure these services before proceeding.

> 💡 **SMT Assembly tip:** If using SMT assembly, make sure your BOM uses LCSC part numbers, as JLCPCB sources components directly from LCSC and will match by those IDs. You can look up parts at [lcsc.com](https://lcsc.com).

---

## Step 6: Place Your Order

1. Add the order to your cart.
2. Proceed to checkout and provide your shipping address.
3. Choose your preferred shipping method.

---

## Step 7: Make Payment

Complete the payment to finalize your order.

---

## Step 8: Track Your Order

After payment, JLCPCB will start production. You can track the production status and shipping updates from your account dashboard.

> 💡 JLCPCB typically takes 24–48 hours for production on standard 2-layer boards. Shipping time varies by method but DHL is usually 3–5 business days to the US.

---

## Step 9: Now just wait patiently, or impatiently...

---

## Pre-Order Checklist

Before hitting that order button, run through this quick checklist:

- [ ] Gerber files verified in a viewer
- [ ] Board dimensions look correct after upload
- [ ] Layer count is set to 2
- [ ] Quantity is correct
- [ ] Shipping address is correct
- [ ] Applied any available coupons/discounts
- [ ] If using SMT assembly: BOM and CPL (component placement) files are uploaded
