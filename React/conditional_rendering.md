it's a way to render different UI based on condition there is 3 ways 

- Early return (if):
    we use early returns for the whole component show a different state like loding, errors or empty screens

- Ternary ( ? : )
    ternary is for rendering one thing or another like if the user is loged out render login page if not render hoe page

- Logical AND (&&) :
    it's eaither render something or don't render at all like if there is an error render error message else render nothing 

** on logical AND React can render 0 so it will render even if we don't want to 

** we can return null to render nothing