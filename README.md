# flask_db_admin
Database administration using Click, Flask and Alembic

## Usage

In your main admin script

    import click
    import flask_db_admin

    @click.group()
    def cli():
        """Main cli interface."""
        pass

    cli.add_command(flask_db_admin.cli)
