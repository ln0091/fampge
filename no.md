from cs50 import SQL
from flask import Flask, redirect, render_template, request

@app.route("/")
def index():
    return render_template("index.html")
