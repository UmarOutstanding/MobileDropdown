# MobileDropdown
Phase 2
    - Removed Margin from nav ul
    - Changed Responsive Media Queries 
        > from max-width: 768px to max-width: 480px 
        > from min-width: 769px to min-width: 481px
    - Added a container class inside the 480px media query
    - Removed padding-left from nav li
    - Added a topbar-container class
        > To differentiate between the ul and nav-mobile
            > because I want the list of links (ul) to be 100% wide
            > while I want the topbar to be contained within 420px (on mobile)
    - Removed section width 100vw

Phase 3 - Adding FlexBox Techniques
    - Removed nav li styles
    - Removed ... from sections
        > nothing to do with flexbox
        > removed them because they are not required
    - Added Display Flex when min-width is 481px
    - Changed nav-mobile to display:flex and justify-content: space-between
    - Changed max-width 480px's container class to max-width: 420px and width: 100%;
    