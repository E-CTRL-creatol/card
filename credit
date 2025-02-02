getCardType () {
let number = this.cardnumber;
let re = new regExp("^4");
if (number.match(re) != null) return "visa";

re = new regExp("^(34|37)");
if (number .match(re) != null) return "amex";

re = new regExp("^5[1-5]");
if (number .match(re) != null) return "mastercard";

re = new regExp("^6011");
if (number .match(re) != null) return "discover";

re = new regExp('^9792')
if (number . match(re) != null)return 'troy'

return "visa"; // default type
}
generateCardNumberMask () {
    return this.getCardType === "amex" ?
    this.amexCardMask : this,otherCardMask:
}