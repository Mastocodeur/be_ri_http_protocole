



# Pour ceux qui travaillent sur Jupyter ou Collab :

Passez l'argument margin-top à 0

    def display_header(header,value):
        display_html(
            "<code style='display:block; margin-top:0; font-family:Consolas,monospace'><b>{}:</b> {}</code>",
            header, value)