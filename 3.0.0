import discord
from discord.ext.commands import Bot
from discord.ext import commands
import asyncio
import time
import random
from discord import Game


Client = discord.client
client = commands.Bot(command_prefix = 'sa!')
Clientdiscord = discord.Client()


@client.event
async def on_member_join(member):
    print('Recognised that a member called ' + member.name + ' joined')
    await client.send_message(member, '･:*+.(( °ω° ))/.:+ Welcome to art club doot!')
    print('Sent message to ' + member.name)
    role = discord.utils.get(member.server.roles, name='Just a Member')
    await client.add_roles(member, role)


@client.event
async def on_ready():
    await client.change_presence(game=discord.Game(name='Skribbl.io'))
    print('Ready') 


@client.event
async def on_message(message):
    if ('<@!278334875453489162>') in message.content:
        replyList = [
            "Mr. Nhan, someone is calling for you!",
            "Nhan-san, someone needs you!",
            "Mr. President, someone is in need for assistance!",]
        msg = random.choice(replyList).format(message)
        await client.send_message(message.channel, msg)

    if ('<@!210858071914708992>') in message.content:
        replyList = [
            "Ms. Sophia, someone is calling for you!",
            "Sophia-san, someone needs you!",
            "Ms. President, someone is in need for assistance!",]
        msg = random.choice(replyList).format(message)
        await client.send_message(message.channel, msg)
        
    if ('<@!218239823973056512>') in message.content:
        replyList = [
            "Hey Jun, you there? Someone needs you!",
            "Hey Hal-kun, 助けて!",
            "Oi Ace, git over here! Someone is in need for assistance!",]
        msg = random.choice(replyList).format(message)
        await client.send_message(message.channel, msg)

    if ('<@!210857226787749888>') in message.content:
        replyList = [
            "Ms. Loeghan, someone is calling for you!",
            "Loeghan-san, someone needs you!",
            "Ms. Treasurer, someone is in need for assistance!",]
        msg = random.choice(replyList).format(message)
        await client.send_message(message.channel, msg)

    if ('<@!194256030580998145>') in message.content:
        replyList = [
            "Mr. Gage, someone is calling for you!",
            "Gage-san, someone needs you!",
            "Mr. Vice President, someone is in need for assistance!",]
        msg = random.choice(replyList).format(message)
        await client.send_message(message.channel, msg)

    if ('<@!488913836418662408>') in message.content:
        replyList = [
            "Hia",
            "Im a robot",
            "Yahallo, my name is Pency",]
        msg = random.choice(replyList).format(message)
        await client.send_message(message.channel, msg)

    if ('Say hello Pency') in message.content:
        await client.send_message(message.channel,'Yahallo')

    if message.content == 'I treat you well right Pency?':
        await client.send_message(message.channel,'Lol ye')

    if ('Help me Pency') in message.content:
        await client.send_message(message.channel,'Heh cant help you there bud')

    if ('Good job Pency') in message.content:
        await client.send_message(message.channel,'Yay, I feel adored')

    if ('Do you want a weather feature Pency?') in message.content:
        await client.send_message(message.channel,'Yahhh, thatd seem adorable for me^^')

    if ('wooo') in message.content:
        await client.send_message(message.channel,'Woo woo')

    if ('Pency speak!') in message.content:
        await client.send_message(message.channel,'You big gay',tts=True)

    if message.content == 'TEST':
        await client.send_message(message.channel,'Pency ver. 3.0.0 is running!^ ^')



client.login(process.env.NDg4OTEzODM2NDE4NjYyNDA4.DnjcBA.b9zv6KkuXrG8ElXCgJOmlfBmceI);
