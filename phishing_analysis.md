# Phishing Email Analysis

## 1. Sample Email
**Subject:** Urgent: Your Account Will Be Suspended  
**From:** support@micr0s0ft-secure.com

**Body:**
> Dear User,  
> We noticed unusual login attempts to your Microsoft account.  
> Please verify your account immediately by clicking the link below:  
> [Verify Now](http://micr0s0ft-security-check.ru/login)

---

## 2. Analysis

### Spoofed Sender Address
- Address: `support@micr0s0ft-secure.com`
- Issue: Uses a fake domain (`micr0s0ft` with zero).

### Header Discrepancies
- Check with: [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx)
- Likely issues: SPF/DKIM failures.

### Suspicious Link
- `http://micr0s0ft-security-check.ru/login`
- Uses `.ru` domain and fake Microsoft brand.

### Urgent Language
- "Failure to do so within 24 hours..." creates fear.

### Mismatched URL
- Hovering shows a different domain than expected.

### Spelling/Grammar
- Slight grammatical issues and robotic tone.

---

## 3. Summary of Phishing Traits

| Trait | Found? |
|-------|--------|
| Fake sender address | ✅ |
| Suspicious link | ✅ |
| Threatening language | ✅ |
| URL mismatch | ✅ |
| Header issues | ✅ |
| Grammar errors | ✅ |
