# Whatsapp Integration with Ecommerce
"Ecommerce giants can use the WhatsApp Business platform or Whatsapp API for their e-commerce stores. By having a Whatsapp-integrated e-commerce store, they can consistently stay in touch with their customers, and increase brand recognition and recall Ultimately, they can use Whatsapp Business for e-commerce to improve the most important factor behind any business success – customer experiences.   Idea is to create whatsapp shop using whatsapp business APIs"
Order Objects (sales_order)
{{var order.id}},
{{var order.state}},
{{var order.status}},
{{var order.coupon_code}},
{{var order.shipping_description}},
{{var order.base_grand_total}},
{{var order.base_shipping_amount}},
{{var order.base_subtotal}},
{{var order.base_tax_amount}},
{{var order.discount_amount}},
{{var order.grand_total}},
{{var order.shipping_amount}},
{{var order.shipping_tax_amount}},
{{var order.subtotal}},
{{var order.tax_amount}},
{{var order.total_qty_ordered}},
{{var order.increment_id}},
{{var order.customer_email}},
{{var order.customer_firstname}},
{{var order.customer_lastname}},
{{var order.order_currency_code}},
{{var order.store_name}},
{{var order.created_at}},
---------------------------------------
INVOICE Objects (sales_invoice)
---------------------------------------
{{var invoice.id}},
{{var invoice.tax_amount}},
{{var invoice.base_grand_total}},
{{var invoice.subtotal}},
{{var invoice.grand_total}},
{{var invoice.shipping_amount}},
{{var invoice.shipping_tax_amount}},
{{var invoice.total_qty}},
{{var invoice.order_id}},
{{var invoice.increment_id}},
{{var invoice.created_at}}
---------------------------------------
SHIPMENT Objects (sales_shipment)
---------------------------------------
{{var shipment.id}},
{{var shipment.increment_id}},
{{var shipment.total_qty}},
{{var shipment.order_id}},
{{var shipment.customer_note}},
{{var shipment.created_at}},
---------------------------------------
Credit Memo Objects (sales_creditmemo)
---------------------------------------
{{var creditmemo.id}},
{{var creditmemo.increment_id}},
{{var creditmemo.grand_total}},
{{var creditmemo.shipping_amount}},
{{var creditmemo.base_subtotal}},
{{var creditmemo.subtotal}},
{{var creditmemo.tax_amount}},
{{var creditmemo.order_id}},
{{var creditmemo.created_at}},
---------------------------------------
CUSTOMER Objects (customer_entity)
---------------------------------------
{{var customer.id}}
{{var customer.firstname}}
{{var customer.lastname}}
{{var customer.email}}
{{var customer.created_in}}
{{var customer.created_at}}"
