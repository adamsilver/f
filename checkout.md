# Checkout

As we discussed in X, One Thing Per Page is wonderfully fruitful design pattern when it comes to complex forms or forms that require a lot of information. A checkout flow is another good example of this.

Let's analyse a typical checkout flow consisting of:

- Delivery options
- Delivery address
- Payment options
- Payment
- Confirmation

## The order of the forms and fields

We don't ask for payment first. We ask for that last. When we type an address, we ask for it in a sensible order for people to understand etc. Makes things more human and conversational.

## Do we really need to ask for it?

### Guest checkout

This might seem slightly off topic for a book dedicated to the design of forms, but this comes under the *must I ask it for it* rule. 300 million dollar button.

### Valid from date

This isn't really needed. Ask Oyvind. Steven.

## Size of the fields

> Baymard institute usability study found that if a field is too long or too short, users start to wonder if they correctly understood the label. This was especially true for fields with uncommon data or a technical label like CVV (card verification code).

Address the address in this.

http://baymard.com/blog/form-field-usability-matching-user-expectations

The width of a field should provide a clue to the length of content it requires. The length of the content provides a clue to the type of content. Both of which help the user fill in a form field.

For example, a postcode is made up of about 8 characters including an optional space. This field should be smaller than other fields in an address form.

If the width of the postcode field is larger to match the other fields, then there's a cognitive burden on the user. They may have to double check the label for example.

![]Good/bad example of address form.

You can apply these principles to other form fields where the length of the field is known. For example, you wouldn't want to apply this principle to street and town because those values could be any length.

## Visual step indicator

When we have a flow like this a step indicator is essential.

## Address lookup enhancement.

## Revealing a billing address if different from delivery.

Checkbox is okay because its for state as well as value.

Can talk about specifying delivery address first or payment address first. Either way an address is necessary.

Could we put a checkbox USE THIS FOR BILLING ON DELIVERY ADDRESS - probably not its a distraction at the wrong time.

Can always use a smart default, so default it to checked on the payment page.

## Payment card choose automatic js enhancemen

Do I really advocate this? Probably not.

## Should we ask for it?

In A Registration Form, we talked about the need to explain to user why they should complete the form, why should they register. Depending on the form and the field we should also be explaining why we are asking for that information specifically.

For example Kidly delivery address, asking for mobile phone, in order to send them notifications. We should tell the user why we are asking for their mobile phone. And if there is no good reason to ask for it, that should drive our design to realise that we shouldn't ask for it, period.

