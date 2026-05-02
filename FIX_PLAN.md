# Fix Plan: AttributesTable and AccordionLinks Typos

## Investigation Steps
1. Search packages/jaeger-ui/src for AttributesTable component
2. Search packages/jaeger-ui/src for AccordionLinks component  
3. Identify typos in:
   - CSS class names
   - Style property keys
   - Component class names
4. Fix identified typos
5. Run test suite: npm test
6. Verify UI builds correctly

## Files to Check
- packages/jaeger-ui/src/components/AttributesTable*
- packages/jaeger-ui/src/components/AccordionLinks*
- packages/jaeger-ui/src/**/*[Aa]ttribute*
- packages/jaeger-ui/src/**/*[Aa]ccordion*

## Testing
- Existing test suite must pass
- Visual regression testing recommended
- Check all references to fixed class names

---
This is a draft PR. Please review the plan and implement the fixes.

