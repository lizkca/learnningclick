Why why tell me why
====================

```

"""a cli game,use keyboard a lot."""
  
import click
import random

commodity = {"water": 100,"book": 30, "car": 1000, "dog": 50}

def need_cmd():
    for k, v in commodity.items():
        click.echo(k,v)
        click.echo("what's your choice?")
        print(commodity)


@click.command()
@click.option(
    "--cmd", prompt="please keep typing the f j key.", help="keep what use typing"
)
def cli(cmd):
    click.echo(f"you have typed {cmd} key.")


if __name__ == "__main__":
    cli()
    need_cmd()
~                                                                                                                                                                            
~                                                                                                                                                                            
~  ```                                                                                                                                                                          
why it did not print dic?~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
~                                                                                                                                                                            
"simmarket.py" 25L, 504C

