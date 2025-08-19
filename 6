// Stripe or similar payment integration
async function processPayment(invoiceId) {
    const invoice = await API.getInvoice(invoiceId);
    
    const stripe = Stripe('your-publishable-key');
    const { error } = await stripe.confirmCardPayment(
        invoice.paymentIntentSecret,
        {
            payment_method: {
                card: cardElement,
                billing_details: {
                    name: invoice.customerName,
                    email: invoice.customerEmail
                }
            }
        }
    );
    
    if (!error) {
        await API.updateInvoiceStatus(invoiceId, 'paid');
    }
}
